<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="DIWHALE & CO. — Independent Financial House">
<title>DIWHALE & CO. | Independent Financial House</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header class="header">
  <a class="logo" href="#home" onclick="closeMenu()">DIWHALE <span>& CO.</span></a>
  <button class="menu-btn" aria-label="Open menu" onclick="toggleMenu()">☰</button>
  <nav class="nav" id="nav">
    <a href="#home">Home</a>
    <a href="#businesses">Our Businesses</a>
    <a href="#about">About Us</a>
    <a href="#insights">Insights</a>
    <a href="#newsroom">Newsroom</a>
    <a href="#careers">Careers</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>

<section class="page active" id="home">
  
<div class="hero">

    <video class="hero-video" autoplay muted loop playsinline>
        <source src="images/kontol.mp4" type="video/mp4">
    </video>

    <div class="hero-overlay"></div>

    <div class="hero-inner">
      <div class="eyebrow" id="slide-label">INDEPENDENT FINANCIAL HOUSE</div>
      <h1 id="slide-title"> <br> </h1>
      <p class="desc" id="slide-desc"> </p>
    </div>

</div>


  <section class="section narrow">
    <div class="eyebrow">WHO WE ARE</div>
    <h2>An Independent Financial House</h2>
    <p class="lead">We take a long-term perspective in understanding businesses, capital and opportunities.</p>
    <a class="text-link" href="#our-story">Discover Our Story →</a>
  </section>

  <section class="section soft">
    <div class="eyebrow">OUR BUSINESSES</div>
    <h2>What We Do</h2>
    <div class="cards">
      <a class="card" href="#financial-advisory">
        <span class="num">01 / ADVISORY</span>
        <h3>Financial Advisory</h3>
        <p>Independent financial perspectives and advisory support for individual clients.</p>
        <b>Explore Financial Advisory →</b>
      </a>
      <a class="card" href="#investments">
        <span class="num">02 / INVESTMENTS</span>
        <h3>Investments</h3>
        <p>A long-term approach to investing proprietary capital and studying business value.</p>
        <b>Explore Investments →</b>
      </a>
    </div>
  </section>

  <section class="section">
    <div class="eyebrow">OUR PERSPECTIVE</div>
    <h2>Insights</h2>
    <p class="body-copy">Research, observations and perspectives on markets, businesses and capital.</p>
    <div class="carousel-wrap">
      <div class="carousel" id="home-insights">
        <a class="tile" href="#insights"><div class="eyebrow">PERSPECTIVES</div><h3>Understanding Business Value</h3><p>A long-term lens on the fundamentals behind a business.</p></a>
        <a class="tile" href="#insights"><div class="eyebrow">MARKETS</div><h3>Markets and Capital</h3><p>Observations on capital allocation and market dynamics.</p></a>
        <a class="tile" href="#insights"><div class="eyebrow">INVESTING</div><h3>Investment Principles</h3><p>Discipline, patience and independent thinking.</p></a>
      </div>
      <div class="carousel-arrows">
        <button onclick="scrollCarousel('home-insights',-1)">←</button>
        <button onclick="scrollCarousel('home-insights',1)">→</button>
      </div>
    </div>
  </section>

  <section class="section soft">
    <div class="eyebrow">LATEST UPDATES</div>
    <h2>Newsroom</h2>
    <div class="carousel-wrap">
      <div class="carousel" id="home-news">
        <a class="tile" href="#newsroom"><div class="eyebrow">COMPANY</div><h3>Company Announcements</h3><p>Updates and announcements from DIWHALE & CO.</p></a>
        <a class="tile" href="#newsroom"><div class="eyebrow">INSIGHTS</div><h3>Research Notes</h3><p>New perspectives and selected research notes.</p></a>
        <a class="tile" href="#newsroom"><div class="eyebrow">UPDATES</div><h3>Latest Developments</h3><p>Follow developments and updates from the firm.</p></a>
      </div>
      <div class="carousel-arrows">
        <button onclick="scrollCarousel('home-news',-1)">←</button>
        <button onclick="scrollCarousel('home-news',1)">→</button>
      </div>
    </div>
  </section>
</section>

<section class="page" id="about">
  <div class="page-hero">
    <div class="eyebrow">DIWHALE & CO.</div>
    <h1>About Us</h1>
    <p>Our identity, principles and approach to building an independent financial house.</p>
    <div class="mobile-subnav">
      <a href="#our-story">Our Story</a>
      <a href="#our-principles">Our Principles</a>
      <a href="#governance">Corporate Governance</a>
      <a href="#our-people">Our People</a>
    </div>
  </div>
  <div class="section">
    <div class="eyebrow">WHO WE ARE</div>
    <h2>Independent Thinking. Long-Term Perspective.</h2>
    <p class="lead">We are building DIWHALE & CO. with a commitment to thoughtful financial perspectives, responsible conduct and long-term value.</p>
    <div class="cards">
      <a class="card" href="#our-story"><span class="num">01</span><h3>Our Story</h3><p>The thinking and ambition behind DIWHALE & CO.</p><b>Read more →</b></a>
      <a class="card" href="#our-principles"><span class="num">02</span><h3>Our Principles</h3><p>The principles that guide our decisions and conduct.</p><b>Read more →</b></a>
      <a class="card" href="#governance"><span class="num">03</span><h3>Corporate Governance</h3><p>Our developing approach to accountability and governance.</p><b>Read more →</b></a>
      <a class="card" href="#our-people"><span class="num">04</span><h3>Our People</h3><p>The people and capabilities behind the firm.</p><b>Read more →</b></a>
    </div>
  </div>
</section>

<section class="page" id="our-story">
  <div class="page-hero"><div class="eyebrow">ABOUT US</div><h1>Our Story</h1><p>The foundations and ambition of DIWHALE & CO.</p></div>
  <div class="section narrow">
    <div class="eyebrow">OUR BEGINNING</div>
    <h2>Built on Independent Perspective</h2>
    <p class="lead">We established DIWHALE & CO. with a simple ambition: to develop an independent financial house grounded in thoughtful analysis, integrity and a long-term view.</p>
    <p class="body-copy top-space">Our journey begins with learning, disciplined capital allocation and the development of sound financial judgement. We intend to build capabilities carefully, growing in line with our experience, resources and applicable regulatory requirements.</p>
    <div class="notice">DIWHALE & CO. is at an early stage of development. This website describes our direction and intended approach, not a claim of scale, track record or regulatory authorisation.</div>
  </div>
</section>

<section class="page" id="our-principles">
  <div class="page-hero"><div class="eyebrow">ABOUT US</div><h1>Our Principles</h1><p>Four principles that shape our culture, conduct and decisions.</p></div>
  <div class="section">
    <div class="content-grid">
      <div class="principle"><h3>Harmony</h3><p>We value balance, collaboration and considered judgement. We seek to align ambition with responsibility and maintain constructive relationships.</p></div>
      <div class="principle"><h3>Integrity</h3><p>We aim to act honestly, transparently and consistently. Trust must be earned through conduct and upheld through accountability.</p></div>
      <div class="principle"><h3>Loyalty</h3><p>We value commitment to our responsibilities, relationships and long-term purpose, while maintaining independent judgement and ethical standards.</p></div>
      <div class="principle"><h3>Industry</h3><p>We believe in diligence, perseverance and continuous improvement. Meaningful work requires preparation, discipline and sustained effort.</p></div>
    </div>
  </div>
</section>

<section class="page" id="governance">
  <div class="page-hero"><div class="eyebrow">ABOUT US</div><h1>Corporate Governance</h1><p>Accountability, responsible conduct and sound decision-making.</p></div>
  <div class="section narrow">
    <h2>A Responsible Foundation</h2>
    <p class="lead">We recognise that sound governance is essential to building a trusted financial institution.</p>
    <p class="body-copy top-space">As DIWHALE & CO. develops, we intend to establish appropriate policies, controls, risk oversight and compliance processes proportionate to our activities. Any regulated financial services will only be undertaken where the required authorisations and conditions are in place.</p>
  </div>
</section>

<section class="page" id="our-people">
  <div class="page-hero"><div class="eyebrow">ABOUT US</div><h1>Our People</h1><p>Capability, judgement and responsibility.</p></div>
  <div class="section narrow">
    <h2>Built Through Capability</h2>
    <p class="lead">We believe an enduring financial house is built by people who value knowledge, discipline and integrity.</p>
    <p class="body-copy top-space">DIWHALE & CO. is currently at an early, founder-led stage. We will share further information about our team as the organisation develops.</p>
  </div>
</section>

<section class="page" id="businesses">
  <div class="page-hero"><div class="eyebrow">OUR BUSINESSES</div><h1>Our Businesses</h1><p>Our current focus and developing areas of activity.</p></div>
  <div class="section">
    <div class="cards">
      <a class="card" href="#financial-advisory"><span class="num">01</span><h3>Financial Advisory</h3><p>Individual-focused financial advisory direction and independent perspectives.</p><b>Explore →</b></a>
      <a class="card" href="#investments"><span class="num">02</span><h3>Investments</h3><p>Investing proprietary capital with a long-term, research-led approach.</p><b>Explore →</b></a>
    </div>
    <div class="notice">The scope of any financial services is subject to applicable laws and regulatory authorisations. No public offer or solicitation is made through this website.</div>
  </div>
</section>

<section class="page" id="financial-advisory">
  <div class="page-hero"><div class="eyebrow">OUR BUSINESSES</div><h1>Financial Advisory</h1><p>Independent perspectives for individual clients.</p></div>
  <div class="section narrow">
    <h2>Clarity for Financial Decisions</h2>
    <p class="lead">Our long-term direction is to provide thoughtful financial perspectives and advisory support to individuals.</p>
    <p class="body-copy top-space">At this stage, DIWHALE & CO. is developing its capabilities and service framework. The firm does not claim to provide regulated investment advice, manage client assets or offer financial products unless and until all required authorisations are obtained.</p>
  </div>
</section>

<section class="page" id="investments">
  <div class="page-hero"><div class="eyebrow">OUR BUSINESSES</div><h1>Investments</h1><p>A disciplined approach to long-term value and capital allocation.</p></div>
  <div class="section narrow">
    <h2>Investing with a Long-Term View</h2>
    <p class="lead">We study businesses, industries and capital markets with a focus on fundamentals, risk and long-term value creation.</p>
    <p class="body-copy top-space">Our current investment activity is limited to the firm's own capital. This is not an offer to manage third-party funds or accept outside investment. Any future expansion will depend on appropriate structures and regulatory requirements.</p>
  </div>
</section>

<section class="page" id="insights">
  <div class="page-hero"><div class="eyebrow">OUR PERSPECTIVE</div><h1>Insights</h1><p>Ideas and observations on markets, businesses and capital.</p></div>
  <div class="section">
    <div class="cards">
      <div class="card"><span class="num">01 / BUSINESS</span><h3>Understanding Business Value</h3><p>How business fundamentals, competitive position and capital allocation inform long-term value.</p></div>
      <div class="card"><span class="num">02 / MARKETS</span><h3>Markets and Capital</h3><p>Observations on market structure, capital flows and economic developments.</p></div>
      <div class="card"><span class="num">03 / INVESTING</span><h3>Investment Principles</h3><p>Discipline, patience and independent thinking in the investment process.</p></div>
    </div>
    <div class="notice">The materials on this website are general information and do not constitute investment advice or a recommendation to buy or sell any financial instrument.</div>
  </div>
</section>

<section class="page" id="newsroom">
  <div class="page-hero"><div class="eyebrow">LATEST UPDATES</div><h1>Newsroom</h1><p>Company news, announcements and updates.</p></div>
  <div class="section"><h2>Latest Updates</h2><p class="body-copy">Official announcements and company updates will be published here as they become available.</p></div>
</section>

<section class="page" id="careers">
  <div class="page-hero"><div class="eyebrow">CAREERS</div><h1>Build with Purpose</h1><p>We value curiosity, diligence and independent thinking.</p></div>
  <div class="section narrow">
    <h2>Careers at DIWHALE & CO.</h2>
    <p class="lead">As the firm develops, this page will provide information about future opportunities.</p>
    <p class="body-copy top-space">There are currently no published vacancies.</p>
  </div>
</section>

<section class="page" id="contact">
  <div class="page-hero"><div class="eyebrow">GET IN TOUCH</div><h1>Contact</h1><p>For general enquiries, please use the contact details officially published by DIWHALE & CO.</p></div>
  <div class="section narrow">
    <h2>General Enquiries</h2>
    <p class="body-copy">Contact information will be added when an official business email and communication channel are established.</p>
    <div class="notice">Please do not send confidential financial information through this website.</div>
  </div>
</section>

<section class="page" id="privacy">
  <div class="page-hero"><div class="eyebrow">LEGAL</div><h1>Privacy</h1></div>
  <div class="section narrow"><p class="body-copy">This is a draft privacy page. Before publication, DIWHALE & CO. should add its actual data collection practices, contact details, retention policy and applicable legal disclosures.</p></div>
</section>

<section class="page" id="disclaimer">
  <div class="page-hero"><div class="eyebrow">LEGAL</div><h1>Disclaimer</h1></div>
  <div class="section narrow"><p class="body-copy">Website content is for general information only. It is not investment, legal, tax or other professional advice, and does not constitute an offer, solicitation or recommendation. Investment values can rise or fall. Obtain independent professional advice where appropriate.</p></div>
</section>

<section class="page" id="terms">
  <div class="page-hero"><div class="eyebrow">LEGAL</div><h1>Terms of Use</h1></div>
  <div class="section narrow"><p class="body-copy">This draft terms page should be reviewed and completed with the firm's jurisdiction, contact details, permitted website use and applicable legal terms before publication.</p></div>
</section>

</main>

<footer class="footer">
  <div class="footer-top">
    <div>
      <h2>DIWHALE & CO.</h2>
      <div class="eyebrow">INDEPENDENT FINANCIAL HOUSE</div>
    </div>
    <div class="footer-links">
      <a href="#about">About Us</a>
      <a href="#businesses">Our Businesses</a>
      <a href="#insights">Insights</a>
      <a href="#newsroom">Newsroom</a>
      <a href="#contact">Contact</a>
    </div>
  </div>
  <div class="footer-bottom">
    <div class="footer-links">
      <a href="#privacy">Privacy</a>
      <a href="#disclaimer">Disclaimer</a>
      <a href="#terms">Terms of Use</a>
    </div>
    <p class="footer-copyright">© 2026 DIWHALE & CO. All rights reserved.</p>
  </div>
</footer>

<script>


let slideIndex = 0;

function changeSlide(direction) {
 slideIndex = (slideIndex + direction + slideData.length) % slideData.length;
 document.getElementById("slide-label").textContent = slideData[slideIndex].label;
 document.getElementById("slide-title").innerHTML = slideData[slideIndex].title;
 document.getElementById("slide-desc").textContent = slideData[slideIndex].desc;
 document.getElementById("slide-count").textContent = "0" + (slideIndex + 1) + " / 03";
}

function toggleMenu() {
 document.getElementById("nav").classList.toggle("open");
}

function closeMenu() {
 document.getElementById("nav").classList.remove("open");
}

function scrollCarousel(id, direction) {
 document.getElementById(id).scrollBy({
  left: direction * 300,
  behavior: "smooth"
 });
}

function showPage() {
 const id = (location.hash || "#home").slice(1);
 const target = document.getElementById(id) || document.getElementById("home");

 document.querySelectorAll(".page").forEach(page => {
  page.classList.remove("active");
 });

 target.classList.add("active");

 document.querySelectorAll(".nav a").forEach(link => {
  link.classList.toggle("active", link.getAttribute("href") === "#" + id);
 });

 closeMenu();
 window.scrollTo({top: 0, behavior: "instant"});
}

window.addEventListener("hashchange", showPage);
showPage();
</script>

</body>
</html>
