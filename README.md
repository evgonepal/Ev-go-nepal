
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#06120f">
<title>EV Go Nepal | Electric Car Rentals</title>
<style>
:root{--bg:#06120f;--card:#10251d;--green:#a5ff68;--white:#f5faf5;--muted:#b0c2b7}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:var(--bg);color:var(--white);font-family:Arial,sans-serif;line-height:1.6}
a{color:inherit;text-decoration:none}
.wrap{width:92%;max-width:1150px;margin:auto}
header{position:sticky;top:0;z-index:10;background:#06120ff5;border-bottom:1px solid #294338}
nav{min-height:66px;display:flex;align-items:center;justify-content:space-between;gap:12px}
.logo{font-size:20px;font-weight:900}
.green,.logo span{color:var(--green)}
.links{display:flex;gap:15px;font-size:13px}
.btn{display:inline-block;text-align:center;padding:11px 15px;border-radius:7px;background:var(--green);color:#10200d;font-weight:bold;font-size:13px}
.outline{background:transparent;color:white;border:1px solid #668071}
.hero{padding:60px 0 38px;background:radial-gradient(ellipse at 80% 20%,#234b30,transparent 45%),repeating-linear-gradient(135deg,transparent 0 35px,#ffffff04 36px 37px)}
.hero-grid{display:grid;grid-template-columns:1fr 1fr;gap:25px;align-items:center}
.tag{color:var(--green);font-size:11px;letter-spacing:2px;font-weight:bold}
h1{font-size:clamp(40px,6vw,68px);line-height:1.05;letter-spacing:-2px;margin:17px 0}
h2{font-size:clamp(27px,4vw,38px);line-height:1.2;margin:8px 0}
p{margin-top:8px}
.muted{color:var(--muted);font-size:13px}
.actions{display:flex;gap:10px;flex-wrap:wrap;margin:22px 0}
.hero-art{border:1px solid #315442;border-radius:16px;padding:12px;background:linear-gradient(145deg,#19382b,#091712)}
.hero-art svg{display:block;width:100%;height:auto}
section{padding:45px 0}
.fleet{background:radial-gradient(ellipse at top,#153a29,transparent 65%)}
.section-head{display:flex;justify-content:space-between;align-items:end;flex-wrap:wrap;gap:12px;margin-bottom:22px}
.cars{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:14px}
.car{border:1px solid #2d4b3d;border-radius:12px;overflow:hidden;background:linear-gradient(145deg,#11281f,#091611)}
.car-art{height:155px;display:flex;align-items:center;justify-content:center;padding:10px;background:radial-gradient(ellipse,#234334,#0b1b14)}
.car-art svg{width:100%;max-width:310px;height:auto}
.car-info{padding:15px}
.car-info h3{font-size:17px;margin:0}
.car-info p{font-size:12px;color:var(--muted);margin:4px 0}
.pills{display:flex;gap:7px;flex-wrap:wrap;margin:10px 0}
.pill{font-size:10px;border:1px solid #456451;border-radius:30px;padding:3px 8px}
.car-info .btn{display:block;margin-top:12px}
.notice{font-size:12px;color:var(--muted);margin-top:18px}
.services{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:12px}
.tile{padding:18px;border:1px solid #294638;border-radius:11px;background:var(--card)}
.tile h3{font-size:15px;margin:6px 0}
.tile p{font-size:12px;color:var(--muted);margin:0}
.symbol{font-size:25px;color:var(--green)}
.why{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}
.why article{padding:17px;border-left:2px solid var(--green);background:#0c1e17}
.cta{padding:28px;border:1px solid #365b3d;border-radius:15px;background:linear-gradient(120deg,#16452b,#0c251c)}
.cta p{max-width:550px;color:var(--muted)}
footer{border-top:1px solid #294338;padding:25px 0;color:var(--muted);font-size:12px}
@media(min-width:1000px){.cars{grid-template-columns:repeat(5,minmax(0,1fr))}.car-art{height:135px}.car-info{padding:12px}}
@media(max-width:700px){.hero-grid{grid-template-columns:1fr}.hero-art{max-width:500px;margin:auto;width:100%}.cars{grid-template-columns:repeat(2,minmax(0,1fr))}.services{grid-template-columns:repeat(2,minmax(0,1fr))}.why{grid-template-columns:1fr}}
@media(max-width:420px){.wrap{width:94%}.logo{font-size:15px}.links{gap:9px;font-size:11px}.navbook{display:none}.hero{padding-top:38px}.car-art{height:105px;padding:5px}.car-info{padding:9px}.car-info h3{font-size:13px}.car-info .btn{font-size:11px;padding:9px 3px}.pill{font-size:9px}}
</style>
</head>
<body>
<header>
<nav class="wrap">
<a class="logo" href="#home">EV GO <span>NEPAL.</span></a>
<div class="links"><a href="#home">Home</a><a href="#fleet">Fleet</a><a href="#services">Services</a><a href="#contact">Contact</a></div>
<a class="btn navbook" href="#contact">Book a Ride</a>
</nav>
</header>

<main>
<section class="hero" id="home">
<div class="wrap hero-grid">
<div>
<div class="tag">ELECTRIC MOBILITY · NEPAL</div>
<h1>Explore Nepal<br><span class="green">the Electric Way.</span></h1>
<p class="muted">Discover electric car journeys for city rides, airport transfers and trips beyond Kathmandu with EV Go Nepal.</p>
<div class="actions">
<a class="btn" href="https://wa.me/9779761118740?text=Hello%20EV%20Go%20Nepal%2C%20I%20want%20to%20book%20a%20ride.">Book on WhatsApp ↗</a>
<a class="btn outline" href="#fleet">View Our Fleet ↓</a>
</div>
<p class="muted">✓ Direct booking &nbsp; ✓ Electric travel &nbsp; ✓ Clear trip details</p>
</div>
<div class="hero-art">
<div class="tag">EV GO NEPAL / PREMIUM MOBILITY</div>
<svg viewBox="0 0 500 280" role="img" aria-label="Decorative electric SUV illustration">
<defs><linearGradient id="body" x1="0" y1="0" x2="1" y2="1"><stop stop-color="#e0e9df"/><stop offset=".5" stop-color="#779987"/><stop offset="1" stop-color="#304b3c"/></linearGradient></defs>
<ellipse cx="250" cy="226" rx="190" ry="17" fill="#000" opacity=".4"/>
<path d="M43 184 L62 151 Q70 139 99 132 L153 76 Q164 64 185 64 L315 64 Q334 66 351 87 L398 140 L435 154 Q450 163 450 184 L444 202 L44 202Z" fill="url(#body)" stroke="#c8dfce" stroke-width="2"/>
<path d="M126 131 L168 83 Q175 76 190 76 L229 76 L229 132Z" fill="#15372e" stroke="#91b6a2" stroke-width="2"/>
<path d="M240 76 L310 76 Q328 78 339 96 L366 132 L240 132Z" fill="#15372e" stroke="#91b6a2" stroke-width="2"/>
<path d="M47 169 L105 166 L105 181 L46 184Z" fill="#a5ff68"/><path d="M401 157 L439 170 L438 181 L406 177Z" fill="#ff7563"/>
<path d="M238 139 L238 194 M374 140 L387 184" stroke="#344e3d" stroke-width="3"/>
<circle cx="151" cy="200" r="33" fill="#07110d" stroke="#789483" stroke-width="4"/><circle cx="151" cy="200" r="14" fill="#a5ff68"/>
<circle cx="373" cy="200" r="33" fill="#07110d" stroke="#789483" stroke-width="4"/><circle cx="373" cy="200" r="14" fill="#a5ff68"/>
<text x="250" y="265" fill="#a5ff68" font-size="12" text-anchor="middle" letter-spacing="3">MOVE GREEN · EXPLORE MORE</text>
</svg>
</div>
</div>
</section>

<section class="fleet" id="fleet">
<div class="wrap">
<div class="section-head"><div><div class="tag">OUR FLEET</div><h2>Choose Your Perfect Ride</h2></div><p class="muted">Electric vehicles · Enquire for availability</p></div>
<div class="cars">

<article class="car">
<div class="car-art"><svg viewBox="0 0 300 130" role="img" aria-label="Stylized BYD Atto 2 compact SUV"><path d="M20 88L40 65L78 54L103 30Q110 25 126 25H197Q215 30 229 52L250 66L276 77L280 98H20Z" fill="#c7d5ca" stroke="#eff8f0" stroke-width="2"/><path d="M84 53L109 33H142V55H82ZM151 33H193Q205 37 216 55H151Z" fill="#183b30" stroke="#779a86" stroke-width="2"/><path d="M24 79H57V88H22Z" fill="#a5ff68"/><circle cx="79" cy="98" r="20" fill="#08110d" stroke="#718b7a" stroke-width="4"/><circle cx="79" cy="98" r="8" fill="#a5ff68"/><circle cx="226" cy="98" r="20" fill="#08110d" stroke="#718b7a" stroke-width="4"/><circle cx="226" cy="98" r="8" fill="#a5ff68"/></svg></div>
<div class="car-info"><h3>BYD Atto 2</h3><p>Compact electric SUV</p><div class="pills"><span class="pill">5 seats</span><span class="pill">Electric</span></div><a class="btn" href="https://wa.me/9779761118740?text=Enquiry%20for%20BYD%20Atto%202">Enquire Now ↗</a></div>
</article>

<article class="car">
<div class="car-art"><svg viewBox="0 0 300 130" role="img" aria-label="Stylized Tata Nexon EV SUV"><path d="M20 88L38 66L73 55L99 31Q110 25 126 28L197 31Q215 34 230 54L250 67L277 78L280 98H20Z" fill="#65b4cf" stroke="#d3f4ff" stroke-width="2"/><path d="M81 54L106 34H141V56H81ZM150 35H193Q205 38 217 56H150Z" fill="#173947" stroke="#9bd8e8" stroke-width="2"/><path d="M24 79H57V88H22Z" fill="#e9fcff"/><circle cx="79" cy="98" r="20" fill="#08110d" stroke="#91b6c2" stroke-width="4"/><circle cx="79" cy="98" r="8" fill="#a5ff68"/><circle cx="226" cy="98" r="20" fill="#08110d" stroke="#91b6c2" stroke-width="4"/><circle cx="226" cy="98" r="8" fill="#a5ff68"/></svg></div>
<div class="car-info"><h3>Tata Nexon EV</h3><p>Electric SUV</p><div class="pills"><span class="pill">5 seats</span><span class="pill">Electric</span></div><a class="btn" href="https://wa.me/9779761118740?text=Enquiry%20for%20Tata%20Nexon%20EV">Enquire Now ↗</a></div>
</article>

<article class="car">
<div class="car-art"><svg viewBox="0 0 300 130" role="img" aria-label="Stylized BYD Dolphin electric hatchback"><path d="M23 89L40 70L77 60L103 39Q112 31 130 32H191Q210 35 224 57L246 70L275 80L279 99H21Z" fill="#d7b8e9" stroke="#f5e9ff" stroke-width="2"/><path d="M84 59L111 40H142V61H83ZM151 40H189Q204 44 213 61H151Z" fill="#352649" stroke="#c6a9d8" stroke-width="2"/><path d="M24 80H57V89H22Z" fill="#fff"/><circle cx="79" cy="99" r="19" fill="#08110d" stroke="#bda4ca" stroke-width="4"/><circle cx="79" cy="99" r="8" fill="#a5ff68"/><circle cx="226" cy="99" r="19" fill="#08110d" stroke="#bda4ca" stroke-width="4"/><circle cx="226" cy="99" r="8" fill="#a5ff68"/></svg></div>
<div class="car-info"><h3>BYD Dolphin</h3><p>Electric hatchback</p><div class="pills"><span class="pill">5 seats</span><span class="pill">Electric</span></div><a class="btn" href="https://wa.me/9779761118740?text=Enquiry%20for%20BYD%20Dolphin">Enquire Now ↗</a></div>
</article>

<article class="car">
<div class="car-art"><svg viewBox="0 0 300 130" role="img" aria-label="Stylized MG ZS EV SUV"><path d="M20 88L39 65L75 55L101 31Q111 24 128 26H198Q216 30 229 52L250 67L276 77L280 98H20Z" fill="#d4ddd6" stroke="#f4faf5" stroke-width="2"/><path d="M82 54L108 33H142V55H82ZM151 34H194Q205 38 217 55H151Z" fill="#293e36" stroke="#9db7a8" stroke-width="2"/><path d="M24 79H57V88H22Z" fill="#a5ff68"/><circle cx="79" cy="98" r="20" fill="#08110d" stroke="#899c90" stroke-width="4"/><circle cx="79" cy="98" r="8" fill="#a5ff68"/><circle cx="226" cy="98" r="20" fill="#08110d" stroke="#899c90" stroke-width="4"/><circle cx="226" cy="98" r="8" fill="#a5ff68"/></svg></div>
<div class="car-info"><h3>MG ZS EV</h3><p>Electric SUV</p><div class="pills"><span class="pill">5 seats</span><span class="pill">Electric</span></div><a class="btn" href="https://wa.me/9779761118740?text=Enquiry%20for%20MG%20ZS%20EV">Enquire Now ↗</a></div>
</article>

<article class="car">
<div class="car-art"><svg viewBox="0 0 300 130" role="img" aria-label="Stylized BYD Sealion 7 premium SUV"><path d="M19 88L36 69L74 56L107 33Q120 26 139 27H198Q219 33 232 53L250 66L276 78L280 98H19Z" fill="#b8a8e6" stroke="#e9e1ff" stroke-width="2"/><path d="M84 55L113 35H144V57H83ZM153 35H194Q207 39 220 57H153Z" fill="#2b2647" stroke="#c8b8f0" stroke-width="2"/><path d="M24 80H57V89H22Z" fill="#f5f1ff"/><circle cx="79" cy="98" r="20" fill="#08110d" stroke="#afa5d0" stroke-width="4"/><circle cx="79" cy="98" r="8" fill="#a5ff68"/><circle cx="226" cy="98" r="20" fill="#08110d" stroke="#afa5d0" stroke-width="4"/><circle cx="226" cy="98" r="8" fill="#a5ff68"/></svg></div>
<div class="car-info"><h3>BYD Sealion 7</h3><p>Premium electric SUV</p><div class="pills"><span class="pill">5 seats</span><span class="pill">Electric</span></div><a class="btn" href="https://wa.me/9779761118740?text=Enquiry%20for%20BYD%20Sealion%207">Enquire Now ↗</a></div>
</article>

</div>
<p class="notice">Car graphics are illustrative, not actual vehicle photographs. Confirm vehicle availability, model, price and specifications before booking.</p>
</div>
</section>

<section id="services">
<div class="wrap"><div class="tag">OUR SERVICES</div><h2>Travel Made Simple</h2>
<div class="services">
<div class="tile"><div class="symbol">⌂</div><h3>City Rides</h3><p>Enquire about rides around Kathmandu Valley.</p></div>
<div class="tile"><div class="symbol">✈</div><h3>Airport Transfers</h3><p>Arrange airport pickup and drop-off.</p></div>
<div class="tile"><div class="symbol">⌖</div><h3>Private Trips</h3><p>Ask about journeys beyond Kathmandu.</p></div>
<div class="tile"><div class="symbol">↗</div><h3>EV Partnerships</h3><p>EV owners can contact us about partnerships.</p></div>
</div></div>
</section>

<section id="why">
<div class="wrap"><div class="tag">WHY EV GO NEPAL</div><h2>Your Electric Travel Partner</h2>
<div class="why">
<article><h3>Simple Booking</h3><p class="muted">Contact us directly on WhatsApp.</p></article>
<article><h3>Clear Pricing</h3><p class="muted">Confirm your fare before travelling.</p></article>
<article><h3>Travel Options</h3><p class="muted">Ask about available vehicles and routes.</p></article>
</div></div>
</section>

<section id="contact">
<div class="wrap cta"><div class="tag">PLAN YOUR JOURNEY</div><h2>Where would you like to go?</h2>
<p>Send us your pickup location, destination, travel date and passenger count to enquire about your trip.</p>
<a class="btn" href="https://wa.me/9779761118740?text=Hello%20EV%20Go%20Nepal%21%0APickup%3A%20%0ADestination%3A%20%0ADate%3A%20%0APassengers%3A%20">Book on WhatsApp ↗</a>
<div class="muted" style="margin-top:18px">Phone: 9761118740<br>Email: evgonep@gmail.com<br>Kathmandu, Nepal</div>
</div>
</section>
</main>

<footer><div class="wrap"><strong>EV GO <span class="green">NEPAL.</span></strong><p>Move Green. Explore More.</p>© 2026 EV Go Nepal. All rights reserved.</div></footer>
</body>
</html>
