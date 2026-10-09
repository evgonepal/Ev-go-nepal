
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#101b25">
<meta name="description" content="Explore electric vehicle rental options in Nepal with EV Go Nepal. Enquire about city travel, family trips and EV owner partnerships.">
<title>EV Go Nepal | Electric Car Rental</title>

<style>
:root {
  --dark: #101b25;
  --dark2: #192a36;
  --lime: #c5f477;
  --white: #ffffff;
  --paper: #f5f7f5;
  --muted: #66737d;
  --line: #e1e7e3;
  --radius: 20px;
  --shadow: 0 12px 35px rgba(16,27,37,.08);
}
* { box-sizing: border-box; }
html { scroll-behavior: smooth; scroll-padding-top: 90px; }
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background: var(--white);
  color: var(--dark);
  line-height: 1.6;
}
button, input, select, textarea { font: inherit; }
button, a { -webkit-tap-highlight-color: transparent; }
a { color: inherit; text-decoration: none; }
button { cursor: pointer; }
img { max-width: 100%; }
.container { width: min(1140px, 92%); margin: auto; }
section { padding: 76px 0; }
.section-heading { max-width: 650px; margin-bottom: 30px; }
.eyebrow {
  color: #507c22; text-transform: uppercase;
  letter-spacing: 2px; font-size: .76rem; font-weight: 800;
}
h1, h2, h3, p { margin-top: 0; }
h1 { font-size: clamp(2.5rem, 6vw, 4.7rem); line-height: 1.04; letter-spacing: -2px; }
h2 { font-size: clamp(1.9rem, 4vw, 3rem); line-height: 1.12; letter-spacing: -1px; }
h3 { line-height: 1.25; }
p { color: var(--muted); }
.btn {
  display: inline-flex; align-items: center; justify-content: center;
  gap: 8px; padding: 13px 19px; border-radius: 12px;
  font-weight: 800; border: 1px solid transparent; transition: .2s;
}
.btn:hover { transform: translateY(-2px); }
.btn-primary { background: var(--lime); color: var(--dark); }
.btn-dark { background: var(--dark); color: white; }
.btn-outline { border-color: #cbd4d0; background: white; color: var(--dark); }
.btn-small { padding: 10px 13px; font-size: .9rem; }
.full { width: 100%; }
.topbar { background: var(--dark); color: #eaf0f3; font-size: .82rem; padding: 8px 0; }
.topbar-inner { display: flex; justify-content: space-between; gap: 12px; flex-wrap: wrap; }
header {
  position: sticky; top: 0; z-index: 20; background: rgba(255,255,255,.96);
  backdrop-filter: blur(12px); border-bottom: 1px solid var(--line);
}
.nav { min-height: 76px; display: flex; align-items: center; justify-content: space-between; gap: 18px; }
.brand { display: flex; align-items: center; gap: 10px; font-weight: 900; letter-spacing: -.5px; }
.brand-mark {
  width: 43px; height: 43px; display: grid; place-items: center;
  border-radius: 13px; background: var(--lime); font-size: 1.45rem;
}
.brand small { display: block; font-size: .65rem; letter-spacing: 2px; color: var(--muted); }
.nav-links { display: flex; align-items: center; gap: 24px; font-size: .92rem; font-weight: 700; }
.nav-links a:hover { color: #527b28; }
.menu-toggle { display: none; background: white; border: 1px solid var(--line); padding: 10px 13px; border-radius: 10px; }

.hero {
  padding: 66px 0 58px; color: white; overflow: hidden;
  background:
    radial-gradient(ellipse at 85% 20%, rgba(197,244,119,.15), transparent 36%),
    linear-gradient(135deg, #101b25, #1c303c);
}
.hero-grid { display: grid; grid-template-columns: 1.05fr .95fr; align-items: center; gap: 42px; }
.hero h1 { color: white; margin: 16px 0 20px; }
.hero h1 span { color: var(--lime); }
.hero p { color: #c9d5dc; max-width: 540px; font-size: 1.08rem; }
.hero-actions { display: flex; flex-wrap: wrap; gap: 12px; margin: 27px 0; }
.hero .eyebrow { color: var(--lime); }
.trust-row { display: flex; flex-wrap: wrap; gap: 16px; color: #e2e9ec; font-size: .86rem; }
.hero-art {
  position: relative; min-height: 350px; display: flex; align-items: center;
  justify-content: center; border: 1px solid rgba(255,255,255,.12);
  border-radius: 30px; overflow: hidden;
  background: linear-gradient(150deg, #263c48, #15232d);
}
.hero-art::before, .hero-art::after {
  content: ""; position: absolute; border-radius: 50%;
  border: 1px solid rgba(197,244,119,.2); width: 290px; height: 290px;
}
.hero-art::after { width: 390px; height: 390px; }
.hero-car-image { position: relative; z-index: 1; width: 100%; height: 350px; object-fit: contain; padding: 15px; }
.hero-fallback { position: absolute; z-index: 2; text-align: center; padding: 25px; }
.hero-fallback .car-symbol { font-size: 5rem; display: block; }
.hero-fallback strong { display: block; color: white; font-size: 1.2rem; }
.hero-fallback span { color: #c9d5dc; font-size: .85rem; }
.hero-caption {
  position: absolute; z-index: 3; bottom: 16px; left: 16px; right: 16px;
  padding: 14px 16px; border-radius: 14px; background: rgba(16,27,37,.88);
  display: flex; align-items: center; justify-content: space-between; gap: 12px;
}
.hero-caption strong { color: white; }
.hero-caption span { color: var(--lime); font-size: .82rem; }

.quick-strip { padding: 0; position: relative; z-index: 4; margin-top: -20px; }
.quick-box {
  display: grid; grid-template-columns: repeat(3,1fr); gap: 14px;
  background: white; border: 1px solid var(--line); border-radius: 18px;
  box-shadow: var(--shadow); padding: 21px;
}
.quick-item { display: flex; gap: 12px; align-items: center; }
.quick-icon { background: #eff8e3; padding: 12px; border-radius: 12px; font-size: 1.3rem; }
.quick-item strong { display: block; font-size: .95rem; }
.quick-item small { color: var(--muted); }

.cars-section { background: var(--paper); }
.car-tools { display: flex; justify-content: space-between; gap: 14px; flex-wrap: wrap; margin-bottom: 24px; }
.search-box { flex: 1; min-width: 220px; }
.search-box input, .filter-select {
  width: 100%; padding: 13px 14px; border: 1px solid var(--line);
  border-radius: 12px; background: white; outline: none;
}
.search-box input:focus, .filter-select:focus, input:focus, select:focus, textarea:focus {
  border-color: #719a43; box-shadow: 0 0 0 3px rgba(197,244,119,.22);
}
.filter-select { width: 190px; }
.car-grid { display: grid; grid-template-columns: repeat(3, minmax(0,1fr)); gap: 20px; }
.car-card {
  background: white; border: 1px solid var(--line); border-radius: var(--radius);
  overflow: hidden; transition: transform .2s, box-shadow .2s;
}
.car-card:hover { transform: translateY(-4px); box-shadow: var(--shadow); }
.car-picture {
  height: 210px; position: relative; display: grid; place-items: center;
  overflow: hidden; background: linear-gradient(145deg,#e7eee8,#f8faf8);
}
.car-picture img { width: 100%; height: 100%; object-fit: contain; padding: 10px; }
.car-picture img[hidden] { display: none; }
.car-placeholder {
  position: absolute; inset: 0; display: flex; align-items: center; justify-content: center;
  flex-direction: column; gap: 5px; text-align: center;
  background: radial-gradient(ellipse at center,#ffffff,#e8f0e8);
}
.car-placeholder .symbol { font-size: 4.3rem; line-height: 1.2; }
.car-placeholder strong { font-size: 1rem; }
.car-placeholder small { color: var(--muted); }
.car-badge {
  position: absolute; top: 13px; left: 13px; z-index: 2;
  background: var(--lime); color: var(--dark); padding: 5px 9px;
  border-radius: 7px; font-size: .72rem; font-weight: 900;
}
.car-content { padding: 19px; }
.car-type { color: #537c2a; font-size: .75rem; font-weight: 900; text-transform: uppercase; letter-spacing: 1px; }
.car-content h3 { margin: 7px 0; font-size: 1.25rem; }
.car-content p { font-size: .9rem; min-height: 42px; margin-bottom: 13px; }
.car-specs { display: flex; flex-wrap: wrap; gap: 7px; margin-bottom: 18px; }
.spec {
  font-size: .78rem; color: #485761; background: #f2f5f3;
  border-radius: 7px; padding: 5px 8px;
}
.car-actions { display: grid; grid-template-columns: 1fr auto; gap: 8px; }
.no-results { display: none; padding: 30px; text-align: center; color: var(--muted); background: white; border-radius: 14px; }

.booking-section { background: white; }
.booking-grid { display: grid; grid-template-columns: .75fr 1.25fr; gap: 35px; align-items: start; }
.booking-info { padding: 28px; background: var(--dark); color: white; border-radius: 22px; position: sticky; top: 100px; }
.booking-info h3 { font-size: 1.55rem; }
.booking-info p { color: #cbd6dc; }
.booking-info ul { list-style: none; padding: 0; margin: 25px 0 0; }
.booking-info li { padding: 10px 0; color: #edf3f5; border-bottom: 1px solid rgba(255,255,255,.12); }
.booking-form { border: 1px solid var(--line); border-radius: 22px; padding: 27px; box-shadow: var(--shadow); }
.form-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
.field { display: flex; flex-direction: column; gap: 7px; }
.field.full-width { grid-column: 1 / -1; }
.field label { font-weight: 800; font-size: .87rem; }
.field input, .field select, .field textarea {
  width: 100%; padding: 12px 13px; border: 1px solid #d7dfda;
  border-radius: 10px; outline: none; background: white; color: var(--dark);
}
.field textarea { min-height: 90px; resize: vertical; }
.form-note { font-size: .78rem; margin: 12px 0 18px; }

.benefits { background: #f4f7f1; }
.benefit-grid { display: grid; grid-template-columns: repeat(3,1fr); gap: 18px; }
.benefit-card { background: white; padding: 25px; border-radius: 18px; border: 1px solid var(--line); }
.benefit-icon { width: 48px; height: 48px; display: grid; place-items: center; background: #eff8e3; border-radius: 14px; font-size: 1.4rem; margin-bottom: 18px; }
.benefit-card h3 { margin-bottom: 8px; }
.benefit-card p { margin-bottom: 0; font-size: .93rem; }

.partner-section { background: var(--dark); color: white; }
.partner-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 40px; align-items: center; }
.partner-section h2 { color: white; }
.partner-section p { color: #c8d3da; }
.partner-points { display: grid; gap: 12px; margin: 24px 0; }
.partner-point { display: flex; gap: 10px; align-items: flex-start; color: #edf2f4; }
.partner-point span { color: var(--lime); font-weight: 900; }
.partner-card { padding: 28px; border-radius: 22px; background: #1c303c; border: 1px solid rgba(255,255,255,.12); }
.partner-card h3 { color: white; }
.partner-card .field label { color: white; }
.partner-card .field { margin-bottom: 15px; }

.faq-section { background: var(--paper); }
.faq-list { max-width: 800px; display: grid; gap: 10px; }
details { background: white; border: 1px solid var(--line); border-radius: 12px; padding: 17px 19px; }
summary { cursor: pointer; font-weight: 800; }
details p { margin: 12px 0 0; font-size: .93rem; }

.contact-band { padding: 42px 0; background: var(--lime); }
.contact-inner { display: flex; align-items: center; justify-content: space-between; gap: 20px; flex-wrap: wrap; }
.contact-inner h2 { font-size: clamp(1.6rem,3vw,2.4rem); margin-bottom: 8px; }
.contact-inner p { color: #35472a; margin-bottom: 0; }

footer { background: #0b141b; color: white; padding: 48px 0 20px; }
.footer-grid { display: grid; grid-template-columns: 1.4fr 1fr 1fr; gap: 35px; padding-bottom: 30px; }
footer p, footer a, footer li { color: #b9c5cc; font-size: .9rem; }
footer a:hover { color: var(--lime); }
footer h3 { color: white; font-size: 1rem; }
footer ul { list-style: none; padding: 0; display: grid; gap: 8px; }
.footer-bottom { border-top: 1px solid #27343d; padding-top: 18px; display: flex; justify-content: space-between; flex-wrap: wrap; gap: 12px; }
.floating-wa {
  position: fixed; right: 18px; bottom: 18px; z-index: 30;
  width: 57px; height: 57px; display: grid; place-items: center;
  background: #20c968; color: white; border-radius: 50%;
  font-size: 1.6rem; box-shadow: 0 6px 20px rgba(0,0,0,.2);
}
.notice { font-size: .78rem; color: var(--muted); }
[hidden] { display: none !important; }

@media (max-width: 850px) {
  .nav-links {
    display: none; position: absolute; top: 76px; left: 0; right: 0;
    background: white; padding: 20px 4%; border-bottom: 1px solid var(--line);
    flex-direction: column; align-items: stretch; gap: 0;
  }
  .nav-links.open { display: flex; }
  .nav-links a { padding: 12px 0; border-bottom: 1px solid var(--line); }
  .menu-toggle { display: block; }
  .nav .nav-cta { display: none; }
  .hero-grid, .booking-grid, .partner-grid { grid-template-columns: 1fr; }
  .hero-art { min-height: 290px; }
  .hero-car-image { height: 290px; }
  .car-grid { grid-template-columns: repeat(2,minmax(0,1fr)); }
  .booking-info { position: static; }
}
@media (max-width: 580px) {
  section { padding: 55px 0; }
  .topbar-inner { justify-content: center; text-align: center; }
  .hero { padding-top: 45px; }
  .hero-grid { gap: 27px; }
  .hero-art { min-height: 245px; }
  .hero-car-image { height: 245px; }
  .quick-box { grid-template-columns: 1fr; padding: 17px; }
  .quick-item { border-bottom: 1px solid var(--line); padding-bottom: 12px; }
  .quick-item:last-child { border-bottom: 0; padding-bottom: 0; }
  .car-grid { grid-template-columns: 1fr; }
  .car-picture { height: 230px; }
  .car-content p { min-height: 0; }
  .filter-select { width: 100%; }
  .form-grid { grid-template-columns: 1fr; }
  .field.full-width { grid-column: auto; }
  .booking-form, .booking-info, .partner-card { padding: 21px; }
  .benefit-grid { grid-template-columns: 1fr; }
  .footer-grid { grid-template-columns: 1fr; gap: 22px; }
  .contact-inner { align-items: flex-start; }
  .trust-row { gap: 10px; }
}
@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after { scroll-behavior: auto !important; transition: none !important; }
}
</style>
</head>

<body>
<div class="topbar">
  <div class="container topbar-inner">
    <span>⚡ Electric mobility across Nepal</span>
    <span>Booking enquiries: 9761118740</span>
  </div>
</div>

<header>
  <div class="container nav">
    <a class="brand" href="#home" aria-label="EV Go Nepal homepage">
      <span class="brand-mark">⚡</span>
      <span>EV GO NEPAL<small>DRIVE A BETTER JOURNEY</small></span>
    </a>
    <button class="menu-toggle" id="menuToggle" aria-label="Open navigation" aria-expanded="false">☰ Menu</button>
    <nav class="nav-links" id="navLinks" aria-label="Main navigation">
      <a href="#home">Home</a>
      <a href="#cars">Explore EVs</a>
      <a href="#booking">Book a Car</a>
      <a href="#partners">For EV Owners</a>
      <a href="#faq">FAQs</a>
    </nav>
    <a class="btn btn-primary nav-cta" href="#booking">Enquire Now ↗</a>
  </div>
</header>

<main>
<section class="hero" id="home">
  <div class="container hero-grid">
    <div>
      <div class="eyebrow">A smarter way to travel</div>
      <h1>Your journey.<br>Your <span>electric</span> choice.</h1>
      <p>Explore electric car rental options for city travel, family trips, business journeys and adventures across Nepal.</p>
      <div class="hero-actions">
        <a class="btn btn-primary" href="#cars">Explore Cars ↓</a>
        <a class="btn btn-outline" href="#booking">Book an EV ↗</a>
      </div>
      <div class="trust-row">
        <span>✓ Enquire directly</span>
        <span>✓ Flexible trip requests</span>
        <span>✓ Owner partnerships</span>
      </div>
    </div>
    <div class="hero-art">
      <img class="hero-car-image" src="images/hero-ev.jpg" alt="Electric vehicle" onerror="this.hidden=true">
      <div class="hero-fallback">
        <span class="car-symbol">🚙</span>
        <strong>Find your next EV</strong>
        <span>City rides · Family trips · More</span>
      </div>
      <div class="hero-caption">
        <div><strong>EV Go Nepal</strong><br><span>Electric mobility made simple</span></div>
        <span>LET'S GO ↗</span>
      </div>
    </div>
  </div>
</section>

<section class="quick-strip" aria-label="Our service highlights">
  <div class="container quick-box">
    <div class="quick-item"><span class="quick-icon">🚘</span><div><strong>Choose your vehicle</strong><small>Explore available options</small></div></div>
    <div class="quick-item"><span class="quick-icon">📅</span><div><strong>Tell us your plans</strong><small>Share your trip details</small></div></div>
    <div class="quick-item"><span class="quick-icon">💬</span><div><strong>Confirm on WhatsApp</strong><small>Check price and availability</small></div></div>
  </div>
</section>

<section class="cars-section" id="cars">
  <div class="container">
    <div class="section-heading">
      <div class="eyebrow">Explore the collection</div>
      <h2>Find the EV for your journey.</h2>
      <p>Browse example electric vehicle models and tell us which one interests you. Actual rental availability, vehicle specifications and prices must be confirmed before booking.</p>
    </div>

    <div class="car-tools">
      <div class="search-box"><input id="carSearch" type="search" placeholder="Search a model, e.g. Nexon..." aria-label="Search cars"></div>
      <select class="filter-select" id="carFilter" aria-label="Filter vehicles by type">
        <option value="all">All vehicle types</option>
        <option value="suv">Electric SUVs</option>
        <option value="hatchback">Compact cars</option>
        <option value="sedan">Electric sedans</option>
      </select>
    </div>

    <div class="car-grid" id="carGrid">
      <article class="car-card" data-name="BYD Atto 2" data-type="suv">
        <div class="car-picture">
          <span class="car-badge">COMPACT SUV</span>
          <img src="images/byd-atto-2.jpg" alt="BYD Atto 2 electric SUV" loading="lazy" onerror="this.hidden=true">
          <div class="car-placeholder"><span class="symbol">🚙</span><strong>BYD Atto 2</strong><small>Add the matching vehicle photo</small></div>
        </div>
        <div class="car-content">
          <div class="car-type">Electric SUV</div><h3>BYD Atto 2</h3>
          <p>A compact electric SUV option for city travel and everyday journeys.</p>
          <div class="car-specs"><span class="spec">SUV</span><span class="spec">5-seat class*</span><span class="spec">EV</span></div>
          <div class="car-actions"><button class="btn btn-dark btn-small choose-car" data-car="BYD Atto 2">Enquire Now</button><a class="btn btn-outline btn-small" href="#booking">Details</a></div>
        </div>
      </article>

      <article class="car-card" data-name="Tata Nexon EV" data-type="suv">
        <div class="car-picture">
          <span class="car-badge">POPULAR SUV</span>
          <img src="images/tata-nexon-ev.jpg" alt="Tata Nexon EV electric SUV" loading="lazy" onerror="this.hidden=true">
          <div class="car-placeholder"><span class="symbol">🚘</span><strong>Tata Nexon EV</strong><small>Add the matching vehicle photo</small></div>
        </div>
        <div class="car-content">
          <div class="car-type">Electric SUV</div><h3>Tata Nexon EV</h3>
          <p>A versatile SUV option to ask about for family and city trips.</p>
          <div class="car-specs"><span class="spec">SUV</span><span class="spec">5-seat class*</span><span class="spec">EV</span></div>
          <div class="car-actions"><button class="btn btn-dark btn-small choose-car" data-car="Tata Nexon EV">Enquire Now</button><a class="btn btn-outline btn-small" href="#booking">Details</a></div>
        </div>
      </article>

      <article class="car-card" data-name="BYD Dolphin" data-type="hatchback">
        <div class="car-picture">
          <span class="car-badge">CITY OPTION</span>
          <img src="images/byd-dolphin.jpg" alt="BYD Dolphin electric hatchback" loading="lazy" onerror="this.hidden=true">
          <div class="car-placeholder"><span class="symbol">🚗</span><strong>BYD Dolphin</strong><small>Add the matching vehicle photo</small></div>
        </div>
        <div class="car-content">
          <div class="car-type">Electric hatchback</div><h3>BYD Dolphin</h3>
          <p>A compact electric car option for urban travel and daily use.</p>
          <div class="car-specs"><span class="spec">Compact</span><span class="spec">EV</span><span class="spec">City travel</span></div>
          <div class="car-actions"><button class="btn btn-dark btn-small choose-car" data-car="BYD Dolphin">Enquire Now</button><a class="btn btn-outline btn-small" href="#booking">Details</a></div>
        </div>
      </article>

      <article class="car-card" data-name="MG ZS EV" data-type="suv">
        <div class="car-picture">
          <span class="car-badge">FAMILY OPTION</span>
          <img src="images/mg-zs-ev.jpg" alt="MG ZS EV electric SUV" loading="lazy" onerror="this.hidden=true">
          <div class="car-placeholder"><span class="symbol">🚙</span><strong>MG ZS EV</strong><small>Add the matching vehicle photo</small></div>
        </div>
        <div class="car-content">
          <div class="car-type">Electric SUV</div><h3>MG ZS EV</h3>
          <p>An electric SUV model to enquire about for family journeys.</p>
          <div class="car-specs"><span class="spec">SUV</span><span class="spec">EV</span><span class="spec">Family trips</span></div>
          <div class="car-actions"><button class="btn btn-dark btn-small choose-car" data-car="MG ZS EV">Enquire Now</button><a class="btn btn-outline btn-small" href="#booking">Details</a></div>
        </div>
      </article>

      <article class="car-card" data-name="Tata Tiago EV" data-type="hatchback">
        <div class="car-picture">
          <span class="car-badge">COMPACT CAR</span>
          <img src="images/tata-tiago-ev.jpg" alt="Tata Tiago EV electric hatchback" loading="lazy" onerror="this.hidden=true">
          <div class="car-placeholder"><span class="symbol">🚗</span><strong>Tata Tiago EV</strong><small>Add the matching vehicle photo</small></div>
        </div>
        <div class="car-content">
          <div class="car-type">Electric hatchback</div><h3>Tata Tiago EV</h3>
          <p>A compact EV model to ask about for shorter trips and city travel.</p>
          <div class="car-specs"><span class="spec">Compact</span><span class="spec">EV</span><span class="spec">City travel</span></div>
          <div class="car-actions"><button class="btn btn-dark btn-small choose-car" data-car="Tata Tiago EV">Enquire Now</button><a class="btn btn-outline btn-small" href="#booking">Details</a></div>
        </div>
      </article>

      <article class="car-card" data-name="BYD Atto 3" data-type="suv">
        <div class="car-picture">
          <span class="car-badge">ELECTRIC SUV</span>
          <img src="images/byd-atto-3.jpg" alt="BYD Atto 3 electric SUV" loading="lazy" onerror="this.hidden=true">
          <div class="car-placeholder"><span class="symbol">🚙</span><strong>BYD Atto 3</strong><small>Add the matching vehicle photo</small></div>
        </div>
        <div class="car-content">
          <div class="car-type">Electric SUV</div><h3>BYD Atto 3</h3>
          <p>An electric SUV model to enquire about for longer journeys.</p>
          <div class="car-specs"><span class="spec">SUV</span><span class="spec">EV</span><span class="spec">Trip enquiries</span></div>
          <div class="car-actions"><button class="btn btn-dark btn-small choose-car" data-car="BYD Atto 3">Enquire Now</button><a class="btn btn-outline btn-small" href="#booking">Details</a></div>
        </div>
      </article>
    </div>
    <div class="no-results" id="noResults">No matching models found. Try another search or choose a different category.</div>
    <p class="notice" style="margin-top:18px">*Seating and model details should be checked against the exact vehicle supplied. Model names shown here are examples, not a guarantee of availability. No rental price is confirmed until you receive a quote.</p>
  </div>
</section>

<section class="booking-section" id="booking">
  <div class="container">
    <div class="section-heading">
      <div class="eyebrow">Start your booking enquiry</div>
      <h2>Tell us about your trip.</h2>
      <p>Complete the form and continue to WhatsApp. We can then discuss the vehicle, rental price, pickup location and availability.</p>
    </div>
    <div class="booking-grid">
      <aside class="booking-info">
        <div class="eyebrow">Your next journey starts here</div>
        <h3>Simple. Clear. Convenient.</h3>
        <p>Send your trip details in a few steps. Your enquiry is not a confirmed booking until the details are agreed.</p>
        <ul>
          <li>✓ Choose your preferred vehicle</li>
          <li>✓ Share your dates and destination</li>
          <li>✓ Ask about driver and self-drive options</li>
          <li>✓ Confirm final price and terms directly</li>
        </ul>
        <p style="margin-top:22px;font-size:.82rem">WhatsApp: 9761118740<br>Email: evgonep@gmail.com</p>
      </aside>

      <form class="booking-form" id="bookingForm">
        <h3>Booking details</h3>
        <div class="form-grid">
          <div class="field">
            <label for="customerName">Your name *</label>
            <input id="customerName" name="name" required maxlength="80" autocomplete="name" placeholder="Enter your name">
          </div>
          <div class="field">
            <label for="customerPhone">Your phone number *</label>
            <input id="customerPhone" name="phone" required type="tel" maxlength="25" autocomplete="tel" placeholder="98XXXXXXXX">
          </div>
          <div class="field">
            <label for="vehicle">Preferred vehicle *</label>
            <select id="vehicle" name="vehicle" required>
              <option value="">Select a model</option>
              <option>BYD Atto 2</option>
              <option>Tata Nexon EV</option>
              <option>BYD Dolphin</option>
              <option>MG ZS EV</option>
              <option>Tata Tiago EV</option>
              <option>BYD Atto 3</option>
              <option>Any suitable available EV</option>
            </select>
          </div>
          <div class="field">
            <label for="rentalType">Rental type *</label>
            <select id="rentalType" name="rental" required>
              <option value="">Choose rental type</option>
              <option>With driver</option>
              <option>Self-drive (subject to eligibility)</option>
              <option>Not sure yet</option>
            </select>
          </div>
          <div class="field">
            <label for="travelDate">Pickup date *</label>
            <input id="travelDate" name="date" type="date" required>
          </div>
          <div class="field">
            <label for="duration">Rental duration *</label>
            <select id="duration" name="duration" required>
              <option value="">Choose duration</option>
              <option>Hourly / short trip</option>
              <option>One day</option>
              <option>2–3 days</option>
              <option>4–7 days</option>
              <option>More than one week</option>
              <option>Need advice</option>
            </select>
          </div>
          <div class="field">
            <label for="pickup">Pickup location *</label>
            <input id="pickup" name="pickup" required maxlength="120" placeholder="e.g. Kathmandu">
          </div>
          <div class="field">
            <label for="destination">Destination *</label>
            <input id="destination" name="destination" required maxlength="160" placeholder="Where are you going?">
          </div>
          <div class="field full-width">
            <label for="extra">Extra details (optional)</label>
            <textarea id="extra" name="extra" maxlength="500" placeholder="Passengers, luggage, return trip or other requests"></textarea>
          </div>
        </div>
        <p class="form-note">Your information is placed into a WhatsApp message so you can review it before sending. This form does not store your details on a server.</p>
        <button class="btn btn-primary full" type="submit">Continue to WhatsApp ↗</button>
      </form>
    </div>
  </div>
</section>

<section class="benefits">
  <div class="container">
    <div class="section-heading">
      <div class="eyebrow">Why EV Go Nepal?</div>
      <h2>A simpler way to find an electric car.</h2>
      <p>Our goal is to connect people looking for EV travel options with vehicle owners and rental partners.</p>
    </div>
    <div class="benefit-grid">
      <article class="benefit-card">
        <div class="benefit-icon">🔎</div>
        <h3>Explore options</h3>
        <p>View example models in one place and tell us what suits your trip.</p>
      </article>
      <article class="benefit-card">
        <div class="benefit-icon">💬</div>
        <h3>Direct communication</h3>
        <p>Discuss availability, final pricing, pickup arrangements and terms before confirming.</p>
      </article>
      <article class="benefit-card">
        <div class="benefit-icon">⚡</div>
        <h3>Support EV owners</h3>
        <p>Help connect EV owners with potential rental enquiries through a partnership process.</p>
      </article>
    </div>
  </div>
</section>

<section class="partner-section" id="partners">
  <div class="container partner-grid">
    <div>
      <div class="eyebrow">For electric vehicle owners</div>
      <h2>Own an EV? Let's explore a partnership.</h2>
      <p>EV Go Nepal aims to connect vehicle owners with potential customers. If you own an electric car, send us your details to discuss a possible partnership.</p>
      <div class="partner-points">
        <div class="partner-point"><span>✓</span><div>Share your vehicle model and general availability.</div></div>
        <div class="partner-point"><span>✓</span><div>Discuss rental rates, commission and operating costs before agreeing.</div></div>
        <div class="partner-point"><span>✓</span><div>Agree on insurance, driver eligibility, vehicle condition and responsibilities in writing.</div></div>
      </div>
      <p class="notice" style="color:#bdcbd2">Submitting this form does not guarantee bookings or income. Any partnership depends on a clear agreement and suitable arrangements.</p>
    </div>
    <div class="partner-card">
      <h3>Register your interest</h3>
      <p>Start a conversation about your vehicle.</p>
      <form id="ownerForm">
        <div class="field"><label for="ownerName">Your name *</label><input id="ownerName" required maxlength="80" placeholder="Your name"></div>
        <div class="field"><label for="ownerPhone">WhatsApp number *</label><input id="ownerPhone" required type="tel" maxlength="25" placeholder="Your contact number"></div>
        <div class="field"><label for="ownerCar">Vehicle model *</label><input id="ownerCar" required maxlength="100" placeholder="e.g. BYD Atto 2"></div>
        <div class="field"><label for="ownerCity">Vehicle location *</label><input id="ownerCity" required maxlength="100" placeholder="e.g. Kathmandu"></div>
        <div class="field"><label for="ownerNote">Additional information</label><textarea id="ownerNote" maxlength="350" placeholder="Availability, preferred rental arrangement, etc."></textarea></div>
        <button class="btn btn-primary full" type="submit">Discuss Partnership on WhatsApp ↗</button>
      </form>
    </div>
  </div>
</section>

<section class="faq-section" id="faq">
  <div class="container">
    <div class="section-heading">
      <div class="eyebrow">Frequently asked questions</div>
      <h2>Good to know before you enquire.</h2>
    </div>
    <div class="faq-list">
      <details><summary>How do I book a vehicle?</summary><p>Choose a model, complete the booking enquiry form and continue to WhatsApp. Confirm the price, vehicle availability and all terms before making a booking.</p></details>
      <details><summary>Are all vehicles shown available?</summary><p>No. The models shown are examples. Availability must be checked individually, and some models may not be available for rental.</p></details>
      <details><summary>How much does an EV rental cost?</summary><p>Rates can vary by model, trip distance, rental duration, driver arrangement and other terms. Contact us for a quote for your specific trip.</p></details>
      <details><summary>Can I request a car with a driver?</summary><p>You can select the with-driver option on the enquiry form. Driver availability, route, charges and other arrangements must be confirmed.</p></details>
      <details><summary>Can I request self-drive rental?</summary><p>You can ask about it, but availability, age and licence eligibility, insurance coverage, deposits and rental conditions must be verified with the provider.</p></details>
      <details><summary>Does submitting the form confirm my booking?</summary><p>No. It prepares a WhatsApp enquiry. Your booking is confirmed only after the provider agrees to availability, pricing, payment arrangements and the rental terms.</p></details>
      <details><summary>How can I become an EV owner partner?</summary><p>Complete the owner form to start a conversation. Before listing a vehicle, discuss commission, customer screening, insurance, maintenance, damage responsibilities and payment terms.</p></details>
    </div>
  </div>
</section>

<section class="contact-band">
  <div class="container contact-inner">
    <div>
      <h2>Ready to plan your journey?</h2>
      <p>Tell us what you need and we'll discuss the available options.</p>
    </div>
    <a class="btn btn-dark" href="https://wa.me/9779761118740?text=Hello%20EV%20Go%20Nepal%2C%20I%20would%20like%20to%20ask%20about%20EV%20rental." target="_blank" rel="noopener noreferrer">Chat on WhatsApp ↗</a>
  </div>
</section>
</main>

<footer>
  <div class="container">
    <div class="footer-grid">
      <div>
        <a class="brand" href="#home">
          <span class="brand-mark">⚡</span>
          <span>EV GO NEPAL<small>ELECTRIC MOBILITY</small></span>
        </a>
        <p style="margin-top:18px;max-width:340px">A developing EV rental enquiry and owner-partnership service for journeys across Nepal.</p>
      </div>
      <div>
        <h3>Explore</h3>
        <ul>
          <li><a href="#cars">Vehicle options</a></li>
          <li><a href="#booking">Booking enquiry</a></li>
          <li><a href="#partners">Owner partnership</a></li>
          <li><a href="#faq">FAQs</a></li>
        </ul>
      </div>
      <div>
        <h3>Contact us</h3>
        <ul>
          <li><a href="https://wa.me/9779761118740" target="_blank" rel="noopener noreferrer">WhatsApp: 9761118740</a></li>
          <li><a href="mailto:evgonep@gmail.com">evgonep@gmail.com</a></li>
        </ul>
      </div>
    </div>
    <div class="footer-bottom">
      <span>© <span id="year"></span> EV Go Nepal. All rights reserved.</span>
      <span>Drive thoughtfully. Travel confidently.</span>
    </div>
  </div>
</footer>

<a class="floating-wa" href="https://wa.me/9779761118740?text=Hello%20EV%20Go%20Nepal%2C%20I%20have%20a%20question." target="_blank" rel="noopener noreferrer" aria-label="Contact EV Go Nepal on WhatsApp">☏</a>

<script>
(function () {
  "use strict";

  const WHATSAPP_NUMBER = "9779761118740";
  const menuToggle = document.getElementById("menuToggle");
  const navLinks = document.getElementById("navLinks");

  menuToggle.addEventListener("click", function () {
    const isOpen = navLinks.classList.toggle("open");
    menuToggle.setAttribute("aria-expanded", String(isOpen));
    menuToggle.textContent = isOpen ? "✕ Close" : "☰ Menu";
  });

  navLinks.querySelectorAll("a").forEach(function (link) {
    link.addEventListener("click", function () {
      navLinks.classList.remove("open");
      menuToggle.setAttribute("aria-expanded", "false");
      menuToggle.textContent = "☰ Menu";
    });
  });

  document.getElementById("year").textContent = new Date().getFullYear();

  const today = new Date();
  const localToday = new Date(today.getTime() - today.getTimezoneOffset() * 60000)
    .toISOString().split("T")[0];
  document.getElementById("travelDate").min = localToday;

  // Show the placeholder only when an image fails to load.
  document.querySelectorAll(".car-picture").forEach(function (picture) {
    const img = picture.querySelector("img");
    const placeholder = picture.querySelector(".car-placeholder");
    function updateImageState() {
      placeholder.hidden = !img.hidden;
    }
    img.addEventListener("load", function () {
      img.hidden = false;
      updateImageState();
    });
    img.addEventListener("error", function () {
      img.hidden = true;
      updateImageState();
    });
    if (img.complete && img.naturalWidth > 0) {
      img.hidden = false;
    } else {
      img.hidden = true;
    }
    updateImageState();
  });

  // Vehicle search and category filter.
  const searchInput = document.getElementById("carSearch");
  const filterSelect = document.getElementById("carFilter");
  const cards = Array.from(document.querySelectorAll(".car-card"));
  const noResults = document.getElementById("noResults");

  function filterCars() {
    const query = searchInput.value.trim().toLowerCase();
    const category = filterSelect.value;
    let visible = 0;

    cards.forEach(function (card) {
      const matchesText = card.dataset.name.toLowerCase().includes(query);
      const matchesCategory = category === "all" || card.dataset.type === category;
      const show = matchesText && matchesCategory;
      card.hidden = !show;
      if (show) visible++;
    });
    noResults.style.display = visible ? "none" : "block";
  }

  searchInput.addEventListener("input", filterCars);
  filterSelect.addEventListener("change", filterCars);

  // Car buttons select the vehicle in the enquiry form.
  document.querySelectorAll(".choose-car").forEach(function (button) {
    button.addEventListener("click", function () {
      document.getElementById("vehicle").value = button.dataset.car;
      document.getElementById("booking").scrollIntoView({ behavior: "smooth" });
    });
  });

  function openWhatsApp(message) {
    const url = "https://wa.me/" + WHATSAPP_NUMBER + "?text=" + encodeURIComponent(message);
    window.open(url, "_blank", "noopener,noreferrer");
  }

  document.getElementById("bookingForm").addEventListener("submit", function (event) {
    event.preventDefault();
    const form = event.currentTarget;
    if (!form.reportValidity()) return;

    const data = new FormData(form);
    const message = [
      "Hello EV Go Nepal! I would like to make a rental enquiry.",
      "",
      "Name: " + data.get("name"),
      "Phone: " + data.get("phone"),
      "Preferred vehicle: " + data.get("vehicle"),
      "Rental type: " + data.get("rental"),
      "Pickup date: " + data.get("date"),
      "Duration: " + data.get("duration"),
      "Pickup location: " + data.get("pickup"),
      "Destination: " + data.get("destination"),
      "Extra details: " + (data.get("extra") || "None"),
      "",
      "Please confirm availability, final price and rental terms."
    ].join("\n");

    openWhatsApp(message);
  });

  document.getElementById("ownerForm").addEventListener("submit", function (event) {
    event.preventDefault();
    const form = event.currentTarget;
    if (!form.reportValidity()) return;

    const data = new FormData(form);
    const message = [
      "Hello EV Go Nepal! I am interested in discussing an EV owner partnership.",
      "",
      "Name: " + data.get("ownerName"),
      "Contact number: " + data.get("ownerPhone"),
      "Vehicle model: " + data.get("ownerCar"),
      "Vehicle location: " + data.get("ownerCity"),
      "Additional information: " + (data.get("ownerNote") || "None"),
      "",
      "Please share the partnership process and terms."
    ].join("\n");

    openWhatsApp(message);
  });
})();
</script>
</body>
</html>
