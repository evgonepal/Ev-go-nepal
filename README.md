<html lang="en">
<head>
  <meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="google-site-verification" content="yDXChXRNbQHuw6gyULbifmzHkKFz8mFAdvNxwq0OZCI">
<meta name="description" content="EV Go Nepal offers electric vehicle rental services in Kathmandu, Pokhara, Chitwan and across Nepal. Book an EV for city travel, tours and airport transfers.">
<meta name="keywords" content="EV rental Nepal, electric car rental Kathmandu, BYD rental Nepal, Nexon EV rental, electric taxi Nepal">
<meta name="theme-color" content="#073b35">
<title>EV Go Nepal | Electric Car Rental & Tours</title>

<style>
:root {
  --green: #087f5b;
  --dark: #073b35;
  --lime: #c9f36b;
  --light: #f4f8f5;
  --text: #18352e;
  --muted: #65766f;
  --white: #ffffff;
  --border: #e0e9e3;
  --shadow: 0 12px 32px rgba(7,59,53,.08);
}
* { box-sizing: border-box; margin: 0; padding: 0; }
html { scroll-behavior: smooth; scroll-padding-top: 90px; }
body {
  font-family: Arial, Helvetica, sans-serif;
  color: var(--text);
  background: #fff;
  line-height: 1.6;
}
a { color: inherit; text-decoration: none; }
button, input, select, textarea { font: inherit; }
button { cursor: pointer; }
img { max-width: 100%; }
.container { width: min(1160px, 92%); margin: auto; }
.topbar {
  background: var(--dark); color: white;
  text-align: center; padding: 8px 12px; font-size: 13px;
}
header {
  position: sticky; top: 0; z-index: 20;
  background: rgba(255,255,255,.97);
  border-bottom: 1px solid var(--border);
  backdrop-filter: blur(12px);
}
.nav {
  min-height: 76px; display: flex; align-items: center;
  justify-content: space-between; gap: 20px;
}
.logo { display: flex; align-items: center; gap: 10px; }
.logo-mark {
  width: 44px; height: 44px; border-radius: 14px;
  display: grid; place-items: center;
  background: var(--green); color: white; font-size: 22px;
}
.logo strong { display: block; font-size: 18px; letter-spacing: -.5px; }
.logo small { color: var(--muted); font-size: 11px; letter-spacing: 1.4px; }
.navlinks { display: flex; align-items: center; gap: 23px; font-size: 14px; font-weight: 600; }
.navlinks a:hover { color: var(--green); }
.btn {
  display: inline-flex; align-items: center; justify-content: center;
  border: 0; border-radius: 12px; padding: 13px 19px;
  background: var(--green); color: white; font-weight: 700;
  transition: transform .2s, background .2s;
}
.btn:hover { transform: translateY(-2px); background: var(--dark); }
.btn-light { background: white; color: var(--dark); }
.btn-outline { border: 1px solid var(--border); background: white; color: var(--dark); }
.btn-small { padding: 9px 13px; font-size: 13px; }
.hero {
  padding: 76px 0 65px;
  background:
    radial-gradient(ellipse at 85% 20%, rgba(201,243,107,.22), transparent 36%),
    linear-gradient(135deg,#f4f8f5,#e9f4ec);
  overflow: hidden;
}
.hero-grid {
  display: grid; grid-template-columns: 1.05fr .95fr;
  align-items: center; gap: 48px;
}
.eyebrow {
  display: inline-block; background: #e1f5d0; color: var(--dark);
  padding: 7px 12px; border-radius: 30px; font-size: 12px;
  font-weight: 800; letter-spacing: 1px; text-transform: uppercase;
}
h1 {
  margin: 18px 0; font-size: clamp(38px,5vw,65px);
  line-height: 1.06; letter-spacing: -2.4px; color: var(--dark);
}
h1 span { color: var(--green); }
.hero-copy { color: var(--muted); font-size: 17px; max-width: 540px; }
.hero-actions { display: flex; flex-wrap: wrap; gap: 12px; margin: 26px 0; }
.trust-row { display: flex; flex-wrap: wrap; gap: 18px; color: var(--muted); font-size: 13px; }
.hero-photo {
  position: relative; border-radius: 28px; overflow: hidden;
  min-height: 360px; background: #dce9e0; box-shadow: var(--shadow);
}
.hero-photo img {
  position: absolute; inset: 0; width: 100%; height: 100%;
  object-fit: cover; object-position: center;
}
.photo-label {
  position: absolute; bottom: 18px; left: 18px; right: 18px;
  padding: 16px; border-radius: 16px; color: white;
  background: rgba(7,59,53,.88); backdrop-filter: blur(8px);
}
.photo-label strong { display: block; font-size: 18px; }
.photo-label small { color: #dcece4; }
.stats { padding: 24px 0; border-bottom: 1px solid var(--border); }
.stats-grid { display: grid; grid-template-columns: repeat(4,1fr); gap: 18px; text-align: center; }
.stat strong { display: block; font-size: 22px; color: var(--dark); }
.stat span { font-size: 13px; color: var(--muted); }
section { padding: 76px 0; }
.section-head {
  display: flex; justify-content: space-between; align-items: end;
  gap: 24px; margin-bottom: 30px;
}
.section-head h2 { font-size: clamp(28px,3.5vw,40px); line-height: 1.15; color: var(--dark); letter-spacing: -1px; }
.section-head p { max-width: 520px; color: var(--muted); margin-top: 10px; }
.section-tag { color: var(--green); font-weight: 800; font-size: 12px; letter-spacing: 1.5px; text-transform: uppercase; }
.finder { background: var(--dark); color: white; padding: 28px; border-radius: 22px; margin-top: -2px; }
.finder h3 { font-size: 22px; margin-bottom: 16px; }
.finder-grid { display: grid; grid-template-columns: repeat(4,1fr); gap: 13px; }
.field { display: flex; flex-direction: column; gap: 7px; }
.field label { font-size: 13px; font-weight: 700; }
.field input, .field select, .field textarea {
  width: 100%; padding: 13px 12px; border: 1px solid #dce5df;
  border-radius: 10px; background: white; color: #18352e; outline: none;
}
.field input:focus, .field select:focus, .field textarea:focus {
  border-color: var(--green); box-shadow: 0 0 0 3px #087f5b1b;
}
.finder .btn { align-self: end; min-height: 48px; }
.cars-section { background: var(--light); }
.filter-row { display: flex; flex-wrap: wrap; gap: 9px; margin-bottom: 25px; }
.filter-btn {
  padding: 9px 15px; border: 1px solid var(--border);
  border-radius: 30px; background: white; color: var(--text); font-weight: 700; font-size: 13px;
}
.filter-btn.active, .filter-btn:hover { background: var(--dark); color: white; border-color: var(--dark); }
.car-grid { display: grid; grid-template-columns: repeat(3,1fr); gap: 22px; }
.car-card {
  background: white; border: 1px solid var(--border);
  border-radius: 20px; overflow: hidden; transition: transform .2s, box-shadow .2s;
}
.car-card:hover { transform: translateY(-5px); box-shadow: var(--shadow); }
.car-image { height: 225px; position: relative; overflow: hidden; background: #eaf0ec; }
.car-image img {
  display: block; width: 100%; height: 100%;
  object-fit: contain; object-position: center; padding: 8px;
  transition: transform .35s;
}
.car-card:hover .car-image img { transform: scale(1.04); }
.car-badge {
  position: absolute; top: 13px; left: 13px;
  background: var(--lime); color: var(--dark);
  border-radius: 30px; padding: 6px 10px; font-size: 11px; font-weight: 800;
}
.car-body { padding: 20px; }
.car-title-row { display: flex; align-items: start; justify-content: space-between; gap: 10px; }
.car-title-row h3 { font-size: 19px; color: var(--dark); }
.car-type { font-size: 12px; color: var(--muted); }
.car-desc { margin: 12px 0; color: var(--muted); font-size: 13px; min-height: 42px; }
.car-specs { display: flex; flex-wrap: wrap; gap: 7px; margin-bottom: 18px; }
.spec { background: var(--light); border-radius: 7px; padding: 6px 9px; font-size: 12px; }
.car-actions { display: flex; gap: 9px; }
.car-actions .btn { flex: 1; padding: 11px 8px; font-size: 13px; }
.disclaimer { color: var(--muted); font-size: 12px; margin-top: 18px; }
.dest-grid { display: grid; grid-template-columns: repeat(4,1fr); gap: 16px; }
.dest-card {
  min-height: 210px; padding: 23px; border-radius: 18px;
  display: flex; flex-direction: column; justify-content: end;
  color: white; overflow: hidden; position: relative;
  background: linear-gradient(145deg,#0a5945,#102e2b);
}
.dest-card:nth-child(2) { background: linear-gradient(145deg,#227f70,#153e37); }
.dest-card:nth-child(3) { background: linear-gradient(145deg,#71945d,#274d36); }
.dest-card:nth-child(4) { background: linear-gradient(145deg,#4b716c,#163b3a); }
.dest-card::before { content: "✦"; position: absolute; top: 10px; right: 20px; font-size: 54px; opacity: .15; }
.dest-card h3 { font-size: 22px; }
.dest-card p { color: #e0eee5; font-size: 13px; }
.steps-grid { display: grid; grid-template-columns: repeat(3,1fr); gap: 22px; }
.step { padding: 25px; border: 1px solid var(--border); border-radius: 18px; }
.step-number {
  width: 43px; height: 43px; display: grid; place-items: center;
  border-radius: 13px; background: #e1f5d0; color: var(--dark);
  font-weight: 900; margin-bottom: 18px;
}
.step h3 { margin-bottom: 8px; color: var(--dark); }
.step p { color: var(--muted); font-size: 14px; }
.booking-section { background: var(--light); }
.booking-grid { display: grid; grid-template-columns: .8fr 1.2fr; gap: 35px; align-items: start; }
.booking-info { background: var(--dark); color: white; padding: 30px; border-radius: 22px; }
.booking-info h2 { font-size: 34px; line-height: 1.15; margin: 14px 0; }
.booking-info p { color: #d7e7de; }
.contact-line { margin-top: 20px; padding-top: 16px; border-top: 1px solid #ffffff30; }
.form-card { background: white; border: 1px solid var(--border); border-radius: 22px; padding: 28px; }
.form-card h3 { font-size: 23px; margin-bottom: 6px; color: var(--dark); }
.form-card > p { color: var(--muted); font-size: 14px; margin-bottom: 22px; }
.form-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
.full { grid-column: 1 / -1; }
.form-card .btn { width: 100%; margin-top: 18px; }
.form-note { font-size: 12px; color: var(--muted); margin-top: 10px; }
.owner-section { background: #fff; }
.owner-box {
  display: grid; grid-template-columns: 1fr 1fr; gap: 30px;
  align-items: center; background: #eef7ec; padding: 35px; border-radius: 24px;
}
.owner-box h2 { font-size: 35px; color: var(--dark); line-height: 1.15; margin: 12px 0; }
.owner-box p { color: var(--muted); }
.owner-points { margin: 18px 0; display: grid; gap: 8px; font-size: 14px; }
.faq-list { display: grid; gap: 12px; max-width: 850px; margin: auto; }
details { border: 1px solid var(--border); border-radius: 13px; padding: 17px 19px; background: white; }
summary { cursor: pointer; font-weight: 800; color: var(--dark); }
details p { margin-top: 12px; color: var(--muted); font-size: 14px; }
footer { background: #052c27; color: white; padding: 50px 0 20px; }
.footer-grid { display: grid; grid-template-columns: 1.4fr 1fr 1fr; gap: 30px; }
footer p, footer a { color: #d0e0d8; font-size: 14px; }
footer h3 { margin-bottom: 13px; }
.footer-links { display: grid; gap: 8px; }
.footer-bottom { border-top: 1px solid #ffffff25; margin-top: 30px; padding-top: 18px; font-size: 12px; color: #c1d5ca; }
.whatsapp-float {
  position: fixed; bottom: 20px; right: 20px; z-index: 30;
  display: flex; align-items: center; gap: 8px;
  padding: 14px 18px; border-radius: 40px; background: #20bd68;
  color: white; font-weight: 800; box-shadow: 0 8px 25px #0002;
}
.mobile-menu { display: none; }
.empty-state { display: none; padding: 30px; text-align: center; color: var(--muted); }
@media (max-width: 900px) {
  .navlinks { gap: 13px; font-size: 13px; }
  .nav-cta { display: none; }
  .hero-grid { gap: 25px; }
  .car-grid { grid-template-columns: repeat(2,1fr); }
  .dest-grid { grid-template-columns: repeat(2,1fr); }
  .finder-grid { grid-template-columns: repeat(2,1fr); }
}
@media (max-width: 650px) {
  .nav { min-height: 66px; flex-wrap: wrap; padding: 10px 0; }
  .logo strong { font-size: 16px; }
  .mobile-menu { display: block; border: 1px solid var(--border); background: white; border-radius: 9px; padding: 9px 12px; }
  .navlinks { display: none; width: 100%; flex-direction: column; align-items: stretch; gap: 0; padding-bottom: 8px; }
  .navlinks.open { display: flex; }
  .navlinks a { padding: 11px 4px; border-top: 1px solid var(--border); }
  .hero { padding: 48px 0 38px; }
  .hero-grid { grid-template-columns: 1fr; }
  .hero-photo { min-height: 260px; }
  h1 { letter-spacing: -1.4px; }
  .hero-copy { font-size: 15px; }
  .stats-grid { grid-template-columns: repeat(2,1fr); row-gap: 22px; }
  section { padding: 52px 0; }
  .section-head { display: block; }
  .finder { padding: 20px; }
  .finder-grid { grid-template-columns: 1fr; }
  .car-grid { grid-template-columns: 1fr; }
  .car-image { height: 240px; }
  .dest-grid { grid-template-columns: 1fr 1fr; gap: 10px; }
  .dest-card { min-height: 160px; padding: 16px; }
  .dest-card h3 { font-size: 18px; }
  .steps-grid { grid-template-columns: 1fr; }
  .booking-grid, .owner-box { grid-template-columns: 1fr; }
  .owner-box { padding: 23px; }
  .owner-box h2 { font-size: 29px; }
  .form-card { padding: 20px; }
  .form-grid { grid-template-columns: 1fr; }
  .full { grid-column: auto; }
  .footer-grid { grid-template-columns: 1fr; gap: 24px; }
  .whatsapp-float { bottom: 13px; right: 13px; padding: 12px 15px; font-size: 13px; }
}
</style>
</head>

<body>
<div class="topbar">Electric journeys across Nepal · Book your next ride with EV Go Nepal</div>

<header>
  <div class="container nav">
    <a class="logo" href="#home" aria-label="EV Go Nepal home">
      <span class="logo-mark">⚡</span>
      <span><strong>EV GO NEPAL</strong><small>ELECTRIC JOURNEYS</small></span>
    </a>
    <button class="mobile-menu" id="menuToggle" aria-expanded="false" aria-label="Toggle navigation">☰ Menu</button>
    <nav class="navlinks" id="navlinks">
      <a href="#home">Home</a>
      <a href="#cars">Find an EV</a>
      <a href="#destinations">Destinations</a>
      <a href="#booking">Booking</a>
      <a href="#owners">List your EV</a>
    </nav>
    <a class="btn nav-cta btn-small" href="#booking">Book a Ride ↗</a>
  </div>
</header>

<main>
<section class="hero" id="home">
  <div class="container hero-grid">
    <div>
      <span class="eyebrow">⚡ Smarter travel starts here</span>
      <h1>Explore Nepal.<br><span>Drive Electric.</span></h1>
      <p class="hero-copy">Discover a more comfortable way to travel with electric vehicle rentals for city rides, family holidays, airport transfers and road trips across Nepal.</p>
      <div class="hero-actions">
        <a class="btn" href="#cars">Explore Our EVs →</a>
        <a class="btn btn-outline" href="#booking">Plan Your Trip</a>
      </div>
      <div class="trust-row">
        <span>✓ Easy booking</span>
        <span>✓ Multiple vehicle options</span>
        <span>✓ Personal assistance</span>
      </div>
    </div>
    <div class="hero-photo">
      <img src="https://assets.bydauto.dk/media/h5xdvebe/atto-2_exterior_forfra_textpicker.jpg?height=900&mode=crop&width=1200"
           alt="BYD Atto 2 electric SUV" fetchpriority="high"
           onerror="this.onerror=null;this.src='https://images.carexpert.com.au/cms/v1/media/2022-03-mg-zs-ev-front-headlights-static.jpg';">
      <div class="photo-label">
        <strong>Your next journey, electric.</strong>
        <small>Choose your vehicle. Tell us your plans. We'll help you get started.</small>
      </div>
    </div>
  </div>
</section>

<div class="stats">
  <div class="container stats-grid">
    <div class="stat"><strong>6+</strong><span>EV models to explore</span></div>
    <div class="stat"><strong>Easy</strong><span>WhatsApp enquiries</span></div>
    <div class="stat"><strong>Nepal</strong><span>Travel destinations</span></div>
    <div class="stat"><strong>Flexible</strong><span>Trip enquiries</span></div>
  </div>
</div>

<section id="trip-finder">
  <div class="container">
    <div class="finder">
      <h3>Find a vehicle for your trip</h3>
      <div class="finder-grid">
        <div class="field">
          <label for="tripLocation">Pickup location</label>
          <select id="tripLocation">
            <option>Kathmandu</option><option>Bhaktapur</option><option>Lalitpur</option>
            <option>Pokhara</option><option>Chitwan</option><option>Other location</option>
          </select>
        </div>
        <div class="field">
          <label for="tripType">Trip type</label>
          <select id="tripType">
            <option>City ride</option><option>Airport transfer</option>
            <option>Outstation tour</option><option>Wedding or event</option>
            <option>Daily rental enquiry</option>
          </select>
        </div>
        <div class="field">
          <label for="tripDate">Travel date</label>
          <input id="tripDate" type="date">
        </div>
        <button class="btn btn-light" id="findTrip">Find My EV →</button>
      </div>
    </div>
  </div>
</section>

<section class="cars-section" id="cars">
  <div class="container">
    <div class="section-head">
      <div>
        <span class="section-tag">Our electric fleet</span>
        <h2>Find your perfect ride.</h2>
        <p>Explore popular electric cars for city travel, family journeys and longer trips. Availability and rental rates are confirmed individually.</p>
      </div>
    </div>

    <div class="filter-row" aria-label="Filter vehicles">
      <button class="filter-btn active" data-filter="all">All Vehicles</button>
      <button class="filter-btn" data-filter="suv">Electric SUVs</button>
      <button class="filter-btn" data-filter="compact">Compact EVs</button>
      <button class="filter-btn" data-filter="family">Family Travel</button>
    </div>

    <div class="car-grid" id="carGrid">

      <article class="car-card" data-category="suv family" data-car="BYD Atto 2">
        <div class="car-image">
          <img src="https://assets.bydauto.dk/media/h5xdvebe/atto-2_exterior_forfra_textpicker.jpg?height=600&mode=crop&width=900"
               alt="BYD Atto 2 electric SUV" loading="lazy"
               onerror="this.onerror=null;this.src='https://www.byd.com/material/byd-site/np/atto2/Brochure.pdf';this.style.display='none';">
          <span class="car-badge">Electric SUV</span>
        </div>
        <div class="car-body">
          <div class="car-title-row"><div><h3>BYD Atto 2</h3><span class="car-type">Compact electric SUV</span></div></div>
          <p class="car-desc">A modern compact SUV option for city travel and comfortable everyday journeys.</p>
          <div class="car-specs"><span class="spec">⚡ Fully electric</span><span class="spec">Family-friendly</span><span class="spec">AC</span></div>
          <div class="car-actions"><button class="btn" onclick="bookCar('BYD Atto 2')">Enquire Now</button><a class="btn btn-outline" href="https://www.byd.com/np/car/atto2" target="_blank" rel="noopener">View Model</a></div>
        </div>
      </article>

      <article class="car-card" data-category="suv family" data-car="Tata Nexon EV">
        <div class="car-image">
          <img src="https://cars.tatamotors.bt/images/Features-M.jpg"
               alt="Tata Nexon EV electric SUV" loading="lazy">
          <span class="car-badge">Popular SUV</span>
        </div>
        <div class="car-body">
          <div class="car-title-row"><div><h3>Tata Nexon EV</h3><span class="car-type">Electric SUV</span></div></div>
          <p class="car-desc">A versatile electric SUV option for city use, family rides and selected longer journeys.</p>
          <div class="car-specs"><span class="spec">⚡ Fully electric</span><span class="spec">SUV</span><span class="spec">AC</span></div>
          <div class="car-actions"><button class="btn" onclick="bookCar('Tata Nexon EV')">Enquire Now</button><a class="btn btn-outline" href="https://cars.tatamotors.com.np/utility-vehicles/nexonk3-ev/gallery.php" target="_blank" rel="noopener">View Model</a></div>
        </div>
      </article>

      <article class="car-card" data-category="compact" data-car="BYD Dolphin">
        <div class="car-image">
          <img src="https://www.caetanoretail.es/site/uploads/sites/20/2024/03/byd-dolphin-frontal-blue.jpg"
               alt="Blue BYD Dolphin electric hatchback" loading="lazy">
          <span class="car-badge">City Friendly</span>
        </div>
        <div class="car-body">
          <div class="car-title-row"><div><h3>BYD Dolphin</h3><span class="car-type">Electric hatchback</span></div></div>
          <p class="car-desc">A compact electric car to consider for urban travel and daily trips.</p>
          <div class="car-specs"><span class="spec">⚡ Fully electric</span><span class="spec">Compact</span><span class="spec">AC</span></div>
          <div class="car-actions"><button class="btn" onclick="bookCar('BYD Dolphin')">Enquire Now</button><a class="btn btn-outline" href="https://www.byd.com/np/" target="_blank" rel="noopener">View Model</a></div>
        </div>
      </article>

      <article class="car-card" data-category="suv family" data-car="MG ZS EV">
        <div class="car-image">
          <img src="https://images.carexpert.com.au/cms/v1/media/2022-03-mg-zs-ev-front-headlights-static.jpg"
               alt="Blue MG ZS EV electric SUV" loading="lazy">
          <span class="car-badge">Family SUV</span>
        </div>
        <div class="car-body">
          <div class="car-title-row"><div><h3>MG ZS EV</h3><span class="car-type">Electric SUV</span></div></div>
          <p class="car-desc">An electric SUV choice for passengers who prefer a higher seating position and extra space.</p>
          <div class="car-specs"><span class="spec">⚡ Fully electric</span><span class="spec">SUV</span><span class="spec">AC</span></div>
          <div class="car-actions"><button class="btn" onclick="bookCar('MG ZS EV')">Enquire Now</button><a class="btn btn-outline" href="https://mgmotor.com.np/" target="_blank" rel="noopener">View Model</a></div>
        </div>
      </article>

      <article class="car-card" data-category="compact" data-car="Tata Tiago EV">
        <div class="car-image">
          <img src="https://img.autocarindia.com/mmv_images/colors/20250516045323_Tata_Tiago_EV_Teal_Blue%5B1%5D.png?c=1&h=500&q=90&w=750"
               alt="Tata Tiago EV electric hatchback" loading="lazy">
          <span class="car-badge">Compact EV</span>
        </div>
        <div class="car-body">
          <div class="car-title-row"><div><h3>Tata Tiago EV</h3><span class="car-type">Compact electric hatchback</span></div></div>
          <p class="car-desc">A small electric hatchback to consider for shorter journeys and city travel.</p>
          <div class="car-specs"><span class="spec">⚡ Fully electric</span><span class="spec">Compact</span><span class="spec">AC</span></div>
          <div class="car-actions"><button class="btn" onclick="bookCar('Tata Tiago EV')">Enquire Now</button><a class="btn btn-outline" href="https://cars.tatamotors.com.np/" target="_blank" rel="noopener">View Model</a></div>
        </div>
      </article>

      <article class="car-card" data-category="suv family" data-car="BYD Atto 3">
        <div class="car-image">
          <img src="https://promobydjkt.com/images_detail/atto_3/warna/BYD%20ATTO%203-Surfing-Blue-1.webp"
               alt="Blue BYD Atto 3 electric SUV" loading="lazy">
          <span class="car-badge">Premium SUV</span>
        </div>
        <div class="car-body">
          <div class="car-title-row"><div><h3>BYD Atto 3</h3><span class="car-type">Electric family SUV</span></div></div>
          <p class="car-desc">A roomier electric SUV option for family travel and selected road trips.</p>
          <div class="car-specs"><span class="spec">⚡ Fully electric</span><span class="spec">Family-friendly</span><span class="spec">AC</span></div>
          <div class="car-actions"><button class="btn" onclick="bookCar('BYD Atto 3')">Enquire Now</button><a class="btn btn-outline" href="https://www.byd.com/np/" target="_blank" rel="noopener">View Model</a></div>
        </div>
      </article>

    </div>
    <p class="disclaimer">Vehicle photographs are illustrative model photos and may show different trims or colours from vehicles available for rental in Nepal. Confirm the actual vehicle, availability and rate before booking.</p>
  </div>
</section>

<section id="destinations">
  <div class="container">
    <div class="section-head">
      <div>
        <span class="section-tag">Discover Nepal</span>
        <h2>Your journey, your way.</h2>
        <p>Tell us where you want to go. We'll help you enquire about an appropriate vehicle and route.</p>
      </div>
    </div>
    <div class="dest-grid">
      <a class="dest-card" href="#booking" onclick="setDestination('Kathmandu')"><h3>Kathmandu</h3><p>City rides and airport transfers →</p></a>
      <a class="dest-card" href="#booking" onclick="setDestination('Pokhara')"><h3>Pokhara</h3><p>Lakeside escapes and tours →</p></a>
      <a class="dest-card" href="#booking" onclick="setDestination('Chitwan')"><h3>Chitwan</h3><p>Nature and family trips →</p></a>
      <a class="dest-card" href="#booking" onclick="setDestination('Lumbini')"><h3>Lumbini</h3><p>Heritage and peaceful journeys →</p></a>
    </div>
  </div>
</section>

<section id="how-it-works">
  <div class="container">
    <div class="section-head">
      <div><span class="section-tag">Simple booking</span><h2>Three steps to get moving.</h2></div>
    </div>
    <div class="steps-grid">
      <div class="step"><div class="step-number">01</div><h3>Choose your EV</h3><p>Browse the vehicles and select the model that fits your trip.</p></div>
      <div class="step"><div class="step-number">02</div><h3>Send your details</h3><p>Share your travel date, pickup point, destination and contact details.</p></div>
      <div class="step"><div class="step-number">03</div><h3>Confirm your booking</h3><p>We'll discuss availability, rental price, driver arrangements and trip terms with you.</p></div>
    </div>
  </div>
</section>

<section class="booking-section" id="booking">
  <div class="container booking-grid">
    <div class="booking-info">
      <span class="eyebrow">Plan your journey</span>
      <h2>Let's get you on the road.</h2>
      <p>Send us your requirements on WhatsApp. We'll follow up to discuss vehicle availability and pricing.</p>
      <div class="contact-line"><strong>WhatsApp</strong><p>+977 9761118740</p></div>
      <div class="contact-line"><strong>Email</strong><p>evgonep@gmail.com</p></div>
      <div class="contact-line"><strong>Service</strong><p>EV rental enquiries across Nepal</p></div>
    </div>

    <form class="form-card" id="bookingForm">
      <h3>Request a booking</h3>
      <p>Fill in your trip details to prepare a WhatsApp enquiry.</p>
      <div class="form-grid">
        <div class="field"><label for="customerName">Full name *</label><input id="customerName" required placeholder="Your name"></div>
        <div class="field"><label for="customerPhone">Phone number *</label><input id="customerPhone" required type="tel" placeholder="Your contact number"></div>
        <div class="field"><label for="carChoice">Preferred vehicle *</label>
          <select id="carChoice" required>
            <option value="">Choose a vehicle</option><option>BYD Atto 2</option><option>Tata Nexon EV</option>
            <option>BYD Dolphin</option><option>MG ZS EV</option><option>Tata Tiago EV</option>
            <option>BYD Atto 3</option><option>Any available EV</option>
          </select>
        </div>
        <div class="field"><label for="bookingDate">Travel date *</label><input id="bookingDate" type="date" required></div>
        <div class="field"><label for="pickup">Pickup location *</label><input id="pickup" required placeholder="e.g. Thamel, Kathmandu"></div>
        <div class="field"><label for="destination">Destination *</label><input id="destination" required placeholder="e.g. Pokhara"></div>
        <div class="field"><label for="passengers">Passengers</label><select id="passengers"><option>1–2</option><option>3–4</option><option>5 or more</option></select></div>
        <div class="field"><label for="rentalType">Trip type</label><select id="rentalType"><option>City ride</option><option>Airport transfer</option><option>Outstation tour</option><option>Daily rental</option><option>Other</option></select></div>
        <div class="field full"><label for="extraDetails">Additional details</label><textarea id="extraDetails" rows="3" placeholder="Return date, luggage, special requirements..."></textarea></div>
      </div>
      <button type="submit" class="btn">Send Booking Enquiry on WhatsApp ↗</button>
      <p class="form-note">This form opens WhatsApp with your details. Your booking is not confirmed until availability and price are agreed.</p>
    </form>
  </div>
</section>

<section class="owner-section" id="owners">
  <div class="container">
    <div class="owner-box">
      <div>
        <span class="section-tag">For EV owners</span>
        <h2>Have an electric car? Let's work together.</h2>
        <p>We're interested in connecting with EV owners who want to discuss rental opportunities and potential partnerships.</p>
        <div class="owner-points">
          <span>✓ Share your vehicle details</span>
          <span>✓ Discuss availability and terms</span>
          <span>✓ Explore possible rental enquiries</span>
        </div>
      </div>
      <form id="ownerForm" class="form-card">
        <h3>List your EV</h3>
        <p>Submit your details to start a partnership conversation.</p>
        <div class="form-grid">
          <div class="field"><label for="ownerName">Your name *</label><input id="ownerName" required placeholder="Full name"></div>
          <div class="field"><label for="ownerPhone">WhatsApp number *</label><input id="ownerPhone" required type="tel" placeholder="Contact number"></div>
          <div class="field full"><label for="ownerCar">Vehicle model *</label><input id="ownerCar" required placeholder="e.g. BYD Atto 2"></div>
          <div class="field"><label for="ownerYear">Vehicle year</label><input id="ownerYear" placeholder="e.g. 2025"></div>
          <div class="field"><label for="ownerLocation">Vehicle location *</label><input id="ownerLocation" required placeholder="e.g. Kathmandu"></div>
          <div class="field full"><label for="ownerTerms">Preferred arrangement</label><select id="ownerTerms"><option>Discuss options</option><option>Daily rental</option><option>Trip-based bookings</option><option>Long-term partnership</option></select></div>
        </div>
        <button class="btn" type="submit">Discuss Partnership on WhatsApp ↗</button>
      </form>
    </div>
  </div>
</section>

<section id="faq">
  <div class="container">
    <div class="section-head"><div><span class="section-tag">Need to know</span><h2>Frequently asked questions.</h2></div></div>
    <div class="faq-list">
      <details><summary>How do I book an electric car?</summary><p>Complete the booking enquiry form. It will open WhatsApp so you can send your trip details and discuss availability.</p></details>
      <details><summary>Are the vehicles available with a driver?</summary><p>Driver arrangements depend on the vehicle and booking. Please mention your preference when making an enquiry.</p></details>
      <details><summary>How much does an EV rental cost?</summary><p>Rates depend on the vehicle, duration, route, driver arrangement and other trip requirements. Contact us for a quote before confirming.</p></details>
      <details><summary>Can I book for travel outside Kathmandu?</summary><p>You can enquire about destinations such as Pokhara, Chitwan and Lumbini. Vehicle and route availability must be confirmed first.</p></details>
      <details><summary>Can I list my own electric vehicle?</summary><p>Yes, you can send your vehicle details through the owner form. A partnership is not guaranteed and any terms must be agreed separately.</p></details>
      <details><summary>Does the website take online payments?</summary><p>No. This version sends enquiries through WhatsApp and does not collect online payments or automatically confirm bookings.</p></details>
    </div>
  </div>
</section>
</main>

<footer>
  <div class="container">
    <div class="footer-grid">
      <div>
        <a class="logo" href="#home"><span class="logo-mark">⚡</span><span><strong style="color:white">EV GO NEPAL</strong><small style="color:#c1d5ca">ELECTRIC JOURNEYS</small></span></a>
        <p style="margin-top:16px;max-width:330px">A simple way to enquire about electric vehicle rentals for your next journey in Nepal.</p>
      </div>
      <div><h3>Explore</h3><div class="footer-links"><a href="#cars">Our Vehicles</a><a href="#destinations">Destinations</a><a href="#booking">Book a Ride</a><a href="#owners">Partner With Us</a></div></div>
      <div><h3>Contact Us</h3><div class="footer-links"><a href="https://wa.me/9779761118740" target="_blank" rel="noopener">WhatsApp: +977 9761118740</a><a href="mailto:evgonep@gmail.com">evgonep@gmail.com</a><a href="#faq">FAQs</a></div></div>
    </div>
    <div class="footer-bottom">© <span id="year"></span> EV Go Nepal. All rights reserved. Vehicle availability, pricing and booking terms must be confirmed directly.</div>
  </div>
</footer>

<a class="whatsapp-float" href="https://wa.me/9779761118740?text=Hello%20EV%20Go%20Nepal%2C%20I%20want%20to%20enquire%20about%20an%20EV%20rental." target="_blank" rel="noopener" aria-label="Chat with EV Go Nepal on WhatsApp">☏ WhatsApp</a>

<script>
const WHATSAPP_NUMBER = "9779761118740";

document.getElementById("year").textContent = new Date().getFullYear();

const menuToggle = document.getElementById("menuToggle");
const navlinks = document.getElementById("navlinks");
menuToggle.addEventListener("click", () => {
  const open = navlinks.classList.toggle("open");
  menuToggle.setAttribute("aria-expanded", String(open));
});
navlinks.querySelectorAll("a").forEach(link => {
  link.addEventListener("click", () => {
    navlinks.classList.remove("open");
    menuToggle.setAttribute("aria-expanded", "false");
  });
});

document.querySelectorAll(".filter-btn").forEach(button => {
  button.addEventListener("click", () => {
    document.querySelectorAll(".filter-btn").forEach(b => b.classList.remove("active"));
    button.classList.add("active");
    const filter = button.dataset.filter;
    document.querySelectorAll(".car-card").forEach(card => {
      const categories = card.dataset.category.split(" ");
      card.style.display = filter === "all" || categories.includes(filter) ? "" : "none";
    });
  });
});

function openWhatsApp(message) {
  const url = "https://wa.me/" + WHATSAPP_NUMBER + "?text=" + encodeURIComponent(message);
  window.open(url, "_blank", "noopener");
}

function bookCar(car) {
  document.getElementById("carChoice").value = car;
  document.getElementById("booking").scrollIntoView({behavior:"smooth"});
}

function setDestination(place) {
  document.getElementById("destination").value = place;
}

document.getElementById("findTrip").addEventListener("click", () => {
  const location = document.getElementById("tripLocation").value;
  const type = document.getElementById("tripType").value;
  const date = document.getElementById("tripDate").value;
  document.getElementById("pickup").value = location;
  document.getElementById("rentalType").value = type;
  if (date) document.getElementById("bookingDate").value = date;
  document.getElementById("booking").scrollIntoView({behavior:"smooth"});
  document.getElementById("customerName").focus({preventScroll:true});
});

document.getElementById("bookingForm").addEventListener("submit", event => {
  event.preventDefault();
  const message = [
    "Hello EV Go Nepal! I want to enquire about a booking.",
    "",
    "Name: " + document.getElementById("customerName").value.trim(),
    "Phone: " + document.getElementById("customerPhone").value.trim(),
    "Vehicle: " + document.getElementById("carChoice").value,
    "Travel date: " + document.getElementById("bookingDate").value,
    "Pickup: " + document.getElementById("pickup").value.trim(),
    "Destination: " + document.getElementById("destination").value.trim(),
    "Passengers: " + document.getElementById("passengers").value,
    "Trip type: " + document.getElementById("rentalType").value,
    "Additional details: " + (document.getElementById("extraDetails").value.trim() || "None"),
    "",
    "Please confirm availability and price."
  ].join("\n");
  openWhatsApp(message);
});

document.getElementById("ownerForm").addEventListener("submit", event => {
  event.preventDefault();
  const message = [
    "Hello EV Go Nepal! I am interested in discussing an EV rental partnership.",
    "",
    "Name: " + document.getElementById("ownerName").value.trim(),
    "Phone: " + document.getElementById("ownerPhone").value.trim(),
    "Vehicle: " + document.getElementById("ownerCar").value.trim(),
    "Year: " + (document.getElementById("ownerYear").value.trim() || "Not specified"),
    "Location: " + document.getElementById("ownerLocation").value.trim(),
    "Preferred arrangement: " + document.getElementById("ownerTerms").value,
    "",
    "Please contact me to discuss the terms."
  ].join("\n");
  openWhatsApp(message);
});

// Avoid dates in the past for new enquiries.
const today = new Date();
const localToday = new Date(today.getTime() - today.getTimezoneOffset() * 60000).toISOString().slice(0,10);
document.getElementById("tripDate").min = localToday;
document.getElementById("bookingDate").min = localToday;
</script>
</body>
</html>
