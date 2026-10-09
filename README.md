
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#101713">
<meta name="description" content="EV Go Nepal offers electric vehicle rental enquiries, airport transfers, city rides and EV owner partnerships in Nepal.">
<title>EV Go Nepal | Premium Electric Car Rentals</title>

<style>
:root {
  --bg:#101713;
  --surface:#18221b;
  --surface2:#222e24;
  --green:#b9f36b;
  --text:#f5f7f2;
  --muted:#a6b2a7;
  --border:#303d32;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth;scroll-padding-top:90px}
body{
  margin:0;background:var(--bg);color:var(--text);
  font-family:Arial,Helvetica,sans-serif;line-height:1.65
}
a{color:inherit;text-decoration:none}
button,input,select,textarea{font:inherit}
button,a{-webkit-tap-highlight-color:transparent}
img{max-width:100%}
.container{width:92%;max-width:1160px;margin:auto}
section{padding:76px 0}
h1,h2,h3,p{margin-top:0}
h1,h2,h3{line-height:1.15;letter-spacing:-.7px}
h1{font-size:clamp(39px,6.5vw,72px);margin:17px 0}
h2{font-size:clamp(30px,4.5vw,46px);margin:12px 0}
h3{font-size:21px}
p{overflow-wrap:break-word}
.muted{color:var(--muted)}
.eyebrow{
  color:var(--green);font-size:11px;font-weight:800;
  letter-spacing:2.5px;text-transform:uppercase
}
.section-head{max-width:700px;margin-bottom:32px}
.section-head p{color:var(--muted)}
.btn{
  display:inline-flex;align-items:center;justify-content:center;
  gap:8px;padding:12px 19px;border:1px solid var(--border);
  border-radius:100px;font-weight:750;cursor:pointer;
  transition:transform .2s,background .2s
}
.btn:hover{transform:translateY(-2px)}
.btn-primary{background:var(--green);color:#15200f;border-color:var(--green)}
.btn-outline{background:transparent;color:var(--text)}
.btn-small{font-size:13px;padding:9px 14px}
header{
  position:sticky;top:0;z-index:50;
  background:rgba(16,23,19,.96);backdrop-filter:blur(15px);
  border-bottom:1px solid var(--border)
}
.nav{min-height:74px;display:flex;align-items:center;justify-content:space-between;gap:20px}
.brand{display:flex;align-items:center;gap:10px;font-weight:900;font-size:17px}
.brand-icon{
  display:grid;place-items:center;background:var(--green);
  color:#14200f;width:41px;height:41px;border-radius:13px;font-weight:1000
}
.brand small{display:block;color:var(--muted);font-size:9px;letter-spacing:2px}
.nav-links{display:flex;align-items:center;gap:21px;font-size:13px}
.nav-links a:hover{color:var(--green)}
.menu-btn{
  display:none;color:white;background:var(--surface);
  border:1px solid var(--border);padding:9px 12px;border-radius:10px
}
/* Hero */
.hero{
  padding:76px 0 54px;
  background:
    radial-gradient(ellipse at 83% 30%,rgba(185,243,107,.11),transparent 38%),
    repeating-linear-gradient(135deg,transparent 0,transparent 42px,rgba(255,255,255,.015) 43px,transparent 44px)
}
.hero-grid{display:grid;grid-template-columns:1fr 1fr;align-items:center;gap:38px}
.hero-copy>p{color:var(--muted);max-width:560px;font-size:17px}
.hero-actions{display:flex;gap:12px;flex-wrap:wrap;margin:25px 0}
.hero-points{display:flex;gap:16px;flex-wrap:wrap;color:#d3ded2;font-size:12px}
.hero-image{
  overflow:hidden;min-width:0;border:1px solid var(--border);
  border-radius:25px;background:linear-gradient(145deg,#2b3b2d,#151c17);
  position:relative
}
.hero-image img{
  display:block;width:100%;aspect-ratio:5/4;
  object-fit:cover;object-position:center
}
.hero-image-caption{
  padding:15px 18px;display:flex;justify-content:space-between;
  gap:12px;flex-wrap:wrap;font-size:12px;color:#d7e1d5
}
.hero-image-caption span:last-child{color:var(--green)}
.stats{
  display:grid;grid-template-columns:repeat(3,1fr);gap:1px;
  margin-top:42px;border:1px solid var(--border);
  border-radius:16px;overflow:hidden;background:var(--border)
}
.stat{background:var(--bg);padding:17px}
.stat strong{display:block;color:var(--green);font-size:15px}
.stat span{font-size:11px;color:var(--muted)}
/* Fleet */
#fleet{background:#131a15}
.fleet-grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:20px}
.car-card{
  min-width:0;overflow:hidden;border:1px solid var(--border);
  border-radius:19px;background:var(--surface);
  transition:transform .2s,border-color .2s
}
.car-card:hover{transform:translateY(-4px);border-color:var(--green)}
.car-photo{
  position:relative;overflow:hidden;aspect-ratio:16/10;
  background:#263229
}
.car-photo img{
  display:block;width:100%;height:100%;object-fit:cover;
  object-position:center
}
.car-label{
  position:absolute;top:12px;left:12px;background:#101713ed;
  color:var(--green);font-size:10px;font-weight:bold;
  padding:6px 10px;border-radius:30px
}
.car-info{padding:20px}
.car-info h3{margin:8px 0 5px}
.car-description{font-size:12px;color:var(--muted)}
.car-specs{display:grid;grid-template-columns:1fr 1fr;gap:9px;margin:18px 0}
.car-spec{padding:10px;background:var(--surface2);border-radius:10px;min-width:0}
.car-spec span{display:block;color:var(--muted);font-size:10px}
.car-spec strong{font-size:12px;overflow-wrap:anywhere}
.car-book{display:flex;width:100%;font-size:12px}
.disclaimer{font-size:12px;color:var(--muted);margin-top:23px}
/* Services */
.service-grid,.benefit-grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:17px}
.info-card{padding:23px;background:var(--surface);border:1px solid var(--border);border-radius:17px}
.info-icon{
  display:grid;place-items:center;width:44px;height:44px;
  background:#28372a;color:var(--green);border-radius:13px;
  font-size:21px;margin-bottom:19px
}
.info-card h3{font-size:18px}
.info-card p{color:var(--muted);font-size:13px;margin-bottom:0}
/* About and partnerships */
.split{display:grid;grid-template-columns:1fr 1fr;gap:35px;align-items:center}
.feature-panel{
  padding:30px;border-radius:22px;border:1px solid var(--border);
  background:linear-gradient(145deg,#202d22,#141b16)
}
.check-list{list-style:none;padding:0;margin:23px 0}
.check-list li{margin:13px 0;font-size:14px;color:#d6e0d4}
.check-list li:before{content:"✓";color:var(--green);font-weight:bold;margin-right:10px}
.steps{margin-top:25px}
.step{display:flex;gap:14px;margin:20px 0}
.step-number{
  flex:none;display:grid;place-items:center;width:35px;height:35px;
  background:var(--green);color:#15200f;border-radius:50%;font-weight:bold
}
.step p{color:var(--muted);font-size:13px;margin:5px 0 0}
/* Booking */
#contact{background:#131a15}
.contact-grid{display:grid;grid-template-columns:.8fr 1.2fr;gap:30px;align-items:start}
.contact-detail{margin:20px 0}
.contact-detail span{display:block;color:var(--muted);font-size:12px}
.contact-detail a{font-weight:bold;overflow-wrap:anywhere}
.form-panel{padding:26px;border:1px solid var(--border);border-radius:21px;background:var(--surface)}
.form-grid{display:grid;grid-template-columns:1fr 1fr;gap:15px}
.field{display:flex;flex-direction:column;gap:7px;min-width:0}
.field.full{grid-column:1/-1}
.field label{font-size:12px;font-weight:bold;color:#dfe7dc}
.field input,.field select,.field textarea{
  width:100%;min-width:0;padding:12px;border-radius:10px;
  background:#101713;color:white;border:1px solid #39483b;outline:none
}
.field input:focus,.field select:focus,.field textarea:focus{border-color:var(--green)}
.field select option{background:#18221b}
.field textarea{resize:vertical;min-height:95px}
.form-panel button{width:100%;margin-top:17px}
.form-help{font-size:11px;color:var(--muted);margin:10px 0 0}
/* FAQ */
.faq-list{max-width:800px}
details{padding:19px 0;border-bottom:1px solid var(--border)}
summary{font-size:15px;font-weight:bold;cursor:pointer}
details p{color:var(--muted);font-size:13px;margin:12px 0 0}
footer{padding:42px 0 90px;border-top:1px solid var(--border)}
.footer-grid{display:grid;grid-template-columns:1.4fr 1fr 1fr;gap:30px}
.footer-title{font-weight:bold;margin-bottom:12px}
footer p,footer li{color:var(--muted);font-size:12px}
footer ul{list-style:none;padding:0}
footer li{margin:9px 0}
.copyright{border-top:1px solid var(--border);padding-top:18px;margin-top:25px;color:var(--muted);font-size:11px}
.whatsapp-float{
  position:fixed;bottom:17px;right:17px;z-index:40;
  background:var(--green);color:#15200f;padding:13px 17px;
  border-radius:100px;font-size:13px;font-weight:bold;
  box-shadow:0 5px 25px #0006
}
@media(max-width:950px){
  .hero-grid,.split,.contact-grid{grid-template-columns:1fr}
  .hero-image{max-width:700px}
  .fleet-grid{grid-template-columns:repeat(2,minmax(0,1fr))}
  .service-grid,.benefit-grid{grid-template-columns:repeat(2,minmax(0,1fr))}
}
@media(max-width:650px){
  section{padding:57px 0}
  .nav{min-height:66px}
  .menu-btn{display:block}
  .nav-links{
    display:none;position:absolute;top:66px;left:0;right:0;
    padding:20px 4% 24px;background:#101713;
    border-bottom:1px solid var(--border);
    flex-direction:column;align-items:stretch;gap:17px
  }
  .nav-links.open{display:flex}
  .nav-links .btn{align-self:flex-start}
  .hero{padding-top:48px}
  .hero-grid{gap:26px}
  .stats{margin-top:30px}
  .stat{padding:12px 8px}
  .stat strong{font-size:12px}
  .stat span{font-size:10px}
  .fleet-grid,.service-grid,.benefit-grid{grid-template-columns:1fr}
  .car-photo{aspect-ratio:16/9}
  .form-grid{grid-template-columns:1fr}
  .field.full{grid-column:auto}
  .form-panel,.feature-panel{padding:20px}
  .footer-grid{grid-template-columns:1fr;gap:18px}
}
@media(prefers-reduced-motion:reduce){
  html{scroll-behavior:auto}
  *,*:before,*:after{transition:none!important}
}
</style>
</head>

<body>
<header>
  <div class="container nav">
    <a class="brand" href="#home">
      <span class="brand-icon">EV</span>
      <span>EV GO NEPAL<small>MOVE ELECTRIC</small></span>
    </a>
    <button class="menu-btn" id="menuBtn" aria-expanded="false"
      aria-controls="navLinks" type="button">☰ Menu</button>
    <nav class="nav-links" id="navLinks" aria-label="Main navigation">
      <a href="#fleet">Our Fleet</a>
      <a href="#services">Services</a>
      <a href="#about">About Us</a>
      <a href="#partners">Partner With Us</a>
      <a href="#contact" class="btn btn-primary btn-small">Book a Ride ↗</a>
    </nav>
  </div>
</header>

<main>
<!-- HERO -->
<section class="hero" id="home">
  <div class="container">
    <div class="hero-grid">
      <div class="hero-copy">
        <div class="eyebrow">Electric mobility · Nepal</div>
        <h1>Your Journey.<br>Our <span style="color:var(--green)">Electric</span> Drive.</h1>
        <p>
          Discover a smarter way to travel. EV Go Nepal connects you
          with electric vehicle rental options for city travel,
          airport transfers, business trips and journeys across Nepal.
        </p>
        <div class="hero-actions">
          <a class="btn btn-primary" href="#fleet">Explore Our Fleet ↗</a>
          <a class="btn btn-outline" href="#contact">Plan Your Trip</a>
        </div>
        <div class="hero-points">
          <span>✓ Multiple vehicle options</span>
          <span>✓ Personalised enquiries</span>
          <span>✓ Direct communication</span>
        </div>
      </div>

      <div class="hero-image">
        <img
          src="https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1200&q=85"
          alt="Premium automotive photography"
          fetchpriority="high"
          onerror="this.onerror=null;this.src='https://placehold.co/900x700/202d22/b9f36b?text=EV+Go+Nepal';">
        <div class="hero-image-caption">
          <span>Electric journeys start here.</span>
          <span>EV GO NEPAL</span>
        </div>
      </div>
    </div>

    <div class="stats">
      <div class="stat"><strong>Flexible Travel</strong><span>Choose your trip type</span></div>
      <div class="stat"><strong>Electric Options</strong><span>Explore available EVs</span></div>
      <div class="stat"><strong>Easy Enquiry</strong><span>Contact us directly</span></div>
    </div>
  </div>
</section>

<!-- FLEET -->
<section id="fleet">
  <div class="container">
    <div class="section-head">
      <div class="eyebrow">Discover the collection</div>
      <h2>Find Your Perfect EV.</h2>
      <p>Explore electric vehicle options for your next journey.
      Vehicle availability, exact model, variant and pricing are confirmed individually.</p>
    </div>

    <div class="fleet-grid">

      <article class="car-card">
        <div class="car-photo">
          <span class="car-label">COMPACT SUV</span>
          <img loading="lazy"
            src="https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=900&q=80"
            alt="Automotive photo reference for BYD Atto 2"
            onerror="this.onerror=null;this.src='https://placehold.co/800x500/263128/b9f36b?text=BYD+Atto+2';">
        </div>
        <div class="car-info">
          <div class="eyebrow">01 · Urban explorer</div>
          <h3>BYD Atto 2</h3>
          <div class="car-description">Compact electric SUV</div>
          <div class="car-specs">
            <div class="car-spec"><span>Seating</span><strong>5 passengers</strong></div>
            <div class="car-spec"><span>Power</span><strong>Electric</strong></div>
            <div class="car-spec"><span>Ideal for</span><strong>City trips</strong></div>
            <div class="car-spec"><span>Price</span><strong>Request quote</strong></div>
          </div>
          <a href="#contact" class="btn btn-primary car-book" data-car="BYD Atto 2">Enquire About This Car ↗</a>
        </div>
      </article>

      <article class="car-card">
        <div class="car-photo">
          <span class="car-label">ELECTRIC SUV</span>
          <img loading="lazy"
            src="https://images.unsplash.com/photo-1519641471654-76ce0107ad1b?auto=format&fit=crop&w=900&q=80"
            alt="SUV photo reference for Tata Nexon EV"
            onerror="this.onerror=null;this.src='https://placehold.co/800x500/263128/b9f36b?text=Tata+Nexon+EV';">
        </div>
        <div class="car-info">
          <div class="eyebrow">02 · Everyday comfort</div>
          <h3>Tata Nexon EV</h3>
          <div class="car-description">Compact electric SUV</div>
          <div class="car-specs">
            <div class="car-spec"><span>Seating</span><strong>5 passengers</strong></div>
            <div class="car-spec"><span>Power</span><strong>Electric</strong></div>
            <div class="car-spec"><span>Ideal for</span><strong>City & highway</strong></div>
            <div class="car-spec"><span>Price</span><strong>Request quote</strong></div>
          </div>
          <a href="#contact" class="btn btn-primary car-book" data-car="Tata Nexon EV">Enquire About This Car ↗</a>
        </div>
      </article>

      <article class="car-card">
        <div class="car-photo">
          <span class="car-label">ELECTRIC HATCHBACK</span>
          <img loading="lazy"
            src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=900&q=80"
            alt="Car photo reference for BYD Dolphin"
            onerror="this.onerror=null;this.src='https://placehold.co/800x500/263128/b9f36b?text=BYD+Dolphin';">
        </div>
        <div class="car-info">
          <div class="eyebrow">03 · City explorer</div>
          <h3>BYD Dolphin</h3>
          <div class="car-description">Electric hatchback</div>
          <div class="car-specs">
            <div class="car-spec"><span>Seating</span><strong>5 passengers</strong></div>
            <div class="car-spec"><span>Power</span><strong>Electric</strong></div>
            <div class="car-spec"><span>Ideal for</span><strong>Urban travel</strong></div>
            <div class="car-spec"><span>Price</span><strong>Request quote</strong></div>
          </div>
          <a href="#contact" class="btn btn-primary car-book" data-car="BYD Dolphin">Enquire About This Car ↗</a>
        </div>
      </article>

      <article class="car-card">
        <div class="car-photo">
          <span class="car-label">FAMILY SUV</span>
          <img loading="lazy"
            src="https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?auto=format&fit=crop&w=900&q=80"
            alt="SUV photo reference for MG ZS EV"
            onerror="this.onerror=null;this.src='https://placehold.co/800x500/263128/b9f36b?text=MG+ZS+EV';">
        </div>
        <div class="car-info">
          <div class="eyebrow">04 · Family journeys</div>
          <h3>MG ZS EV</h3>
          <div class="car-description">Electric SUV</div>
          <div class="car-specs">
            <div class="car-spec"><span>Seating</span><strong>5 passengers</strong></div>
            <div class="car-spec"><span>Power</span><strong>Electric</strong></div>
            <div class="car-spec"><span>Ideal for</span><strong>Family trips</strong></div>
            <div class="car-spec"><span>Price</span><strong>Request quote</strong></div>
          </div>
          <a href="#contact" class="btn btn-primary car-book" data-car="MG ZS EV">Enquire About This Car ↗</a>
        </div>
      </article>

      <article class="car-card">
        <div class="car-photo">
          <span class="car-label">ELECTRIC SUV</span>
          <img loading="lazy"
            src="https://images.unsplash.com/photo-1511919884226-fd3cad34687c?auto=format&fit=crop&w=900&q=80"
            alt="Automotive photo reference for another EV option"
            onerror="this.onerror=null;this.src='https://placehold.co/800x500/263128/b9f36b?text=Electric+SUV';">
        </div>
        <div class="car-info">
          <div class="eyebrow">05 · Premium travel</div>
          <h3>BYD Atto 3</h3>
          <div class="car-description">Electric SUV</div>
          <div class="car-specs">
            <div class="car-spec"><span>Seating</span><strong>5 passengers</strong></div>
            <div class="car-spec"><span>Power</span><strong>Electric</strong></div>
            <div class="car-spec"><span>Ideal for</span><strong>Longer journeys</strong></div>
            <div class="car-spec"><span>Price</span><strong>Request quote</strong></div>
          </div>
          <a href="#contact" class="btn btn-primary car-book" data-car="BYD Atto 3">Enquire About This Car ↗</a>
        </div>
      </article>

      <article class="car-card">
        <div class="car-photo">
          <span class="car-label">MORE OPTIONS</span>
          <img loading="lazy"
            src="https://images.unsplash.com/photo-1549317661-bd32c8ce0db2?auto=format&fit=crop&w=900&q=80"
            alt="Automotive photo reference for additional EV rentals"
            onerror="this.onerror=null;this.src='https://placehold.co/800x500/263128/b9f36b?text=More+EV+Options';">
        </div>
        <div class="car-info">
          <div class="eyebrow">06 · Your choice</div>
          <h3>Other EV Models</h3>
          <div class="car-description">Ask about available vehicles</div>
          <div class="car-specs">
            <div class="car-spec"><span>Seating</span><strong>Model dependent</strong></div>
            <div class="car-spec"><span>Power</span><strong>Electric</strong></div>
            <div class="car-spec"><span>Ideal for</span><strong>Your itinerary</strong></div>
            <div class="car-spec"><span>Price</span><strong>Request quote</strong></div>
          </div>
          <a href="#contact" class="btn btn-primary car-book" data-car="Other EV model">Find My EV ↗</a>
        </div>
      </article>

    </div>
    <p class="disclaimer">
      Photo accuracy notice: external photos above are illustrative automotive
      images and are not verified images of the exact listed models. Confirm
      model, variant, specifications, availability and price before booking.
    </p>
  </div>
</section>

<!-- SERVICES -->
<section id="services">
  <div class="container">
    <div class="section-head">
      <div class="eyebrow">Travel your way</div>
      <h2>Services Designed Around You.</h2>
      <p>Tell us where you want to go, and enquire about the right vehicle and trip arrangement.</p>
    </div>
    <div class="service-grid">
      <article class="info-card">
        <div class="info-icon">↗</div>
        <h3>Airport Transfers</h3>
        <p>Enquire about electric car pickups and drop-offs for Kathmandu airport journeys.</p>
      </article>
      <article class="info-card">
        <div class="info-icon">⌖</div>
        <h3>City Travel</h3>
        <p>Explore transport options for meetings, shopping, sightseeing and everyday travel.</p>
      </article>
      <article class="info-card">
        <div class="info-icon">⌁</div>
        <h3>Outstation Trips</h3>
        <p>Discuss your destination, charging stops, itinerary and suitable EV with us.</p>
      </article>
      <article class="info-card">
        <div class="info-icon">▣</div>
        <h3>Business Travel</h3>
        <p>Request transport arrangements for meetings, guests and corporate visits.</p>
      </article>
      <article class="info-card">
        <div class="info-icon">◈</div>
        <h3>Family Journeys</h3>
        <p>Find a suitable vehicle based on passenger numbers, luggage and trip distance.</p>
      </article>
      <article class="info-card">
        <div class="info-icon">⚡</div>
        <h3>EV Rental Enquiries</h3>
        <p>Tell us your preferred model and rental dates to request an availability check.</p>
      </article>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="container split">
    <div>
      <div class="eyebrow">Why EV Go Nepal</div>
      <h2>Modern Mobility.<br>Personal Service.</h2>
      <p class="muted">
        EV Go Nepal is being developed as a convenient way for customers
        to enquire about electric vehicle rentals and connect with vehicle
        owners for suitable travel arrangements.
      </p>
      <ul class="check-list">
        <li>Multiple vehicle choices in one place</li>
        <li>Direct communication about availability and pricing</li>
        <li>Trip planning based on passenger and luggage needs</li>
        <li>Electric mobility options for different journeys</li>
      </ul>
      <a href="#contact" class="btn btn-primary">Talk to Our Team ↗</a>
    </div>
    <div class="feature-panel">
      <div class="eyebrow">Our booking approach</div>
      <h3>Clear. Convenient. Personal.</h3>
      <div class="steps">
        <div class="step">
          <div class="step-number">1</div>
          <div><strong>Choose a vehicle</strong><p>Browse the fleet and select your preferred EV.</p></div>
        </div>
        <div class="step">
          <div class="step-number">2</div>
          <div><strong>Share your trip details</strong><p>Send your date, destination, passenger count and service preference.</p></div>
        </div>
        <div class="step">
          <div class="step-number">3</div>
          <div><strong>Confirm your booking</strong><p>Agree on the final price, vehicle, inclusions and terms before payment.</p></div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- PARTNERS -->
<section id="partners">
  <div class="container split">
    <div class="feature-panel">
      <div class="eyebrow">EV owner network</div>
      <h2>Own an EV?<br>Let's Work Together.</h2>
      <p class="muted">
        We welcome enquiries from electric vehicle owners interested in
        exploring potential rental and travel partnerships.
      </p>
      <ul class="check-list">
        <li>Discuss your vehicle and availability</li>
        <li>Agree on rental rates and payment terms</li>
        <li>Clarify insurance and responsibility for damages</li>
        <li>Set out booking, cancellation and service conditions</li>
      </ul>
      <a class="btn btn-primary" href="#contact" data-partner="yes">Become a Partner ↗</a>
    </div>
    <div>
      <div class="eyebrow">A partnership built on clarity</div>
      <h2>Grow With EV Go Nepal.</h2>
      <p class="muted">
        Our goal is to build a reliable network of vehicle owners and
        customers. Any partnership will depend on agreed terms, customer
        demand and vehicle suitability.
      </p>
      <div class="benefit-grid" style="grid-template-columns:1fr">
        <article class="info-card">
          <h3>01. Share Your Vehicle</h3>
          <p>Tell us your make, model, year and availability.</p>
        </article>
        <article class="info-card">
          <h3>02. Agree on the Terms</h3>
          <p>Discuss rates, operating costs, insurance and responsibilities.</p>
        </article>
        <article class="info-card">
          <h3>03. Explore Bookings</h3>
          <p>Review genuine customer enquiries and confirm each trip before accepting it.</p>
        </article>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT / BOOKING -->
<section id="contact">
  <div class="container">
    <div class="section-head">
      <div class="eyebrow">Let's plan your journey</div>
      <h2>Request a Rental Quote.</h2>
      <p>Fill in the details below. Your enquiry will open in WhatsApp for you to review and send.</p>
    </div>

    <div class="contact-grid">
      <div>
        <h3>Get in Touch</h3>
        <p class="muted">Tell us what you need, and we can discuss vehicle options and trip arrangements.</p>

        <div class="contact-detail">
          <span>WhatsApp / Phone</span>
          <a href="https://wa.me/9779761118740" target="_blank" rel="noopener noreferrer">+977 9761118740</a>
        </div>
        <div class="contact-detail">
          <span>Email</span>
          <a href="mailto:evgonep@gmail.com">evgonep@gmail.com</a>
        </div>
        <div class="contact-detail">
          <span>Service area</span>
          <strong>Kathmandu, Nepal</strong>
        </div>
        <a class="btn btn-primary" href="https://wa.me/9779761118740" target="_blank" rel="noopener noreferrer">
          Chat on WhatsApp ↗
        </a>
      </div>

      <form class="form-panel" id="bookingForm">
        <div class="form-grid">
          <div class="field">
            <label for="customerName">Your name *</label>
            <input id="customerName" name="name" required maxlength="80" placeholder="Enter your name">
          </div>
          <div class="field">
            <label for="customerPhone">Your phone number *</label>
            <input id="customerPhone" name="phone" type="tel" required maxlength="25" placeholder="Your contact number">
          </div>
          <div class="field">
            <label for="carSelect">Preferred vehicle *</label>
            <select id="carSelect" name="car" required>
              <option value="">Select a vehicle</option>
              <option>BYD Atto 2</option>
              <option>Tata Nexon EV</option>
              <option>BYD Dolphin</option>
              <option>MG ZS EV</option>
              <option>BYD Atto 3</option>
              <option>Other EV model</option>
            </select>
          </div>
          <div class="field">
            <label for="tripType">Service type *</label>
            <select id="tripType" name="service" required>
              <option value="">Select service</option>
              <option>City travel</option>
              <option>Airport transfer</option>
              <option>Outstation trip</option>
              <option>Business travel</option>
              <option>Family trip</option>
              <option>EV owner partnership</option>
            </select>
          </div>
          <div class="field">
            <label for="tripDate">Preferred date</label>
            <input id="tripDate" name="date" type="date">
          </div>
          <div class="field">
            <label for="passengers">Passengers</label>
            <select id="passengers" name="passengers">
              <option>1</option><option>2</option><option>3</option>
              <option>4</option><option>5</option><option>6+</option>
            </select>
          </div>
          <div class="field full">
            <label for="tripDetails">Pickup, destination and other details</label>
            <textarea id="tripDetails" name="details" maxlength="1500"
              placeholder="Where are you travelling? Do you need a driver? Any luggage?"></textarea>
          </div>
        </div>
        <button type="submit" class="btn btn-primary">Send Enquiry on WhatsApp ↗</button>
        <p class="form-help">No payment is taken through this form. Your WhatsApp message must be sent by you.</p>
      </form>
    </div>
  </div>
</section>

<!-- FAQ -->
<section id="faq">
  <div class="container">
    <div class="section-head">
      <div class="eyebrow">Helpful information</div>
      <h2>Frequently Asked Questions.</h2>
    </div>
    <div class="faq-list">
      <details>
        <summary>How do I book an electric vehicle?</summary>
        <p>Choose a vehicle, submit the enquiry form and send the generated WhatsApp message. Your booking is not confirmed until availability and terms have been agreed.</p>
      </details>
      <details>
        <summary>How much does an EV rental cost?</summary>
        <p>Pricing depends on the vehicle, trip distance, duration, driver arrangement and included services. Contact us for a quote before confirming.</p>
      </details>
      <details>
        <summary>Can I request a car with a driver?</summary>
        <p>Yes, you can request a driver in your enquiry. Driver availability and charges must be confirmed for your trip.</p>
      </details>
      <details>
        <summary>Are charging costs and parking included?</summary>
        <p>These expenses may vary by booking. Confirm charging, parking, tolls, driver meals or accommodation, overtime and other charges before accepting the quote.</p>
      </details>
      <details>
        <summary>Can I partner with EV Go Nepal as a car owner?</summary>
        <p>Yes, you can enquire about a potential partnership. Vehicle suitability, customer demand, rates, insurance and responsibilities need to be agreed first.</p>
      </details>
      <details>
        <summary>Are the cars shown available right now?</summary>
        <p>The website displays vehicle options for enquiries. Contact us to verify the exact model, vehicle photographs, availability and rental conditions.</p>
      </details>
    </div>
  </div>
</section>
</main>

<footer>
  <div class="container">
    <div class="footer-grid">
      <div>
        <a class="brand" href="#home">
          <span class="brand-icon">EV</span>
          <span>EV GO NEPAL<small>MOVE ELECTRIC</small></span>
        </a>
        <p style="margin-top:17px;max-width:330px">
          Connecting travellers with electric mobility options for journeys across Nepal.
        </p>
      </div>
      <div>
        <div class="footer-title">Explore</div>
        <ul>
          <li><a href="#fleet">Our Fleet</a></li>
          <li><a href="#services">Our Services</a></li>
          <li><a href="#about">About Us</a></li>
          <li><a href="#partners">Partner With Us</a></li>
        </ul>
      </div>
      <div>
        <div class="footer-title">Contact</div>
        <ul>
          <li><a href="https://wa.me/9779761118740" target="_blank" rel="noopener noreferrer">WhatsApp: 9761118740</a></li>
          <li><a href="mailto:evgonep@gmail.com">evgonep@gmail.com</a></li>
          <li>Kathmandu, Nepal</li>
        </ul>
      </div>
    </div>
    <div class="copyright">
      © <span id="year"></span> EV Go Nepal. All rights reserved.
      Vehicle availability, prices and specifications are subject to confirmation.
    </div>
  </div>
</footer>

<a class="whatsapp-float" href="https://wa.me/9779761118740"
  target="_blank" rel="noopener noreferrer" aria-label="Contact EV Go Nepal on WhatsApp">
  WhatsApp ↗
</a>

<script>
(function(){
  "use strict";

  var menuBtn = document.getElementById("menuBtn");
  var navLinks = document.getElementById("navLinks");

  menuBtn.addEventListener("click", function(){
    var open = navLinks.classList.toggle("open");
    menuBtn.setAttribute("aria-expanded", String(open));
    menuBtn.textContent = open ? "✕ Close" : "☰ Menu";
  });

  navLinks.querySelectorAll("a").forEach(function(link){
    link.addEventListener("click", function(){
      navLinks.classList.remove("open");
      menuBtn.setAttribute("aria-expanded", "false");
      menuBtn.textContent = "☰ Menu";
    });
  });

  document.querySelectorAll("[data-car]").forEach(function(link){
    link.addEventListener("click", function(){
      var select = document.getElementById("carSelect");
      var car = link.getAttribute("data-car");
      for (var i = 0; i < select.options.length; i++) {
        if (select.options[i].text === car) {
          select.selectedIndex = i;
          break;
        }
      }
    });
  });

  document.querySelectorAll("[data-partner]").forEach(function(link){
    link.addEventListener("click", function(){
      document.getElementById("tripType").value = "EV owner partnership";
    });
  });

  var dateField = document.getElementById("tripDate");
  var now = new Date();
  var localDate = new Date(now.getTime() - now.getTimezoneOffset() * 60000)
    .toISOString().slice(0,10);
  dateField.min = localDate;

  document.getElementById("bookingForm").addEventListener("submit", function(event){
    event.preventDefault();

    var name = document.getElementById("customerName").value.trim();
    var phone = document.getElementById("customerPhone").value.trim();
    var car = document.getElementById("carSelect").value;
    var service = document.getElementById("tripType").value;
    var date = dateField.value || "Not specified";
    var passengers = document.getElementById("passengers").value;
    var details = document.getElementById("tripDetails").value.trim();

    if (!name || !phone || !car || !service) {
      alert("Please complete all required fields.");
      return;
    }

    var message = [
      "Hello EV Go Nepal! I would like to enquire about a booking.",
      "",
      "Name: " + name,
      "Phone: " + phone,
      "Vehicle: " + car,
      "Service: " + service,
      "Preferred date: " + date,
      "Passengers: " + passengers,
      "Trip details: " + (details || "Not specified"),
      "",
      "Please confirm availability and the total rental price."
    ].join("\n");

    var url = "https://wa.me/9779761118740?text=" + encodeURIComponent(message);
    var opened = window.open(url, "_blank", "noopener,noreferrer");

    if (!opened) {
      window.location.href = url;
    }
  });

  document.getElementById("year").textContent = new Date().getFullYear();
})();
</script>
</body>
</html>
