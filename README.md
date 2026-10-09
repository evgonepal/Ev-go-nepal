
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#103d30">
<meta name="description" content="Discover electric vehicle rentals in Kathmandu and across Nepal with EV Go Nepal.">
<title>EV Go Nepal | Electric Vehicle Rentals</title>
<style>
:root{--green:#145c43;--dark:#103d30;--lime:#c8f36a;--cream:#f6f7f1;--muted:#68766f}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;font-family:Arial,Helvetica,sans-serif;color:#18352b;background:#fff}
a{color:inherit;text-decoration:none}
button,input,select{font:inherit}
.topbar{background:var(--dark);color:white;padding:10px 6%;font-size:13px;display:flex;justify-content:space-between;gap:12px;flex-wrap:wrap}
header{padding:18px 6%;display:flex;align-items:center;justify-content:space-between;gap:20px;flex-wrap:wrap;border-bottom:1px solid #e8ece7}
.logo{font-size:24px;font-weight:900;letter-spacing:-1px;color:var(--dark)}
.logo span{color:#25865b}
nav{display:flex;gap:22px;align-items:center;flex-wrap:wrap;font-size:14px;font-weight:600}
.navbtn,.btn{display:inline-block;background:var(--green);color:white;padding:13px 19px;border-radius:7px;font-weight:700;border:0;cursor:pointer}
.hero{padding:64px 6% 48px;background:linear-gradient(130deg,#f3f6ed,#e2f0df)}
.eyebrow{font-size:12px;text-transform:uppercase;letter-spacing:2px;font-weight:800;color:var(--green)}
h1{font-size:clamp(38px,6vw,65px);line-height:1.05;letter-spacing:-2px;max-width:750px;margin:16px 0}
h1 span{color:#28794f}
.lead{font-size:17px;line-height:1.7;color:#52645a;max-width:620px}
.hero-actions{display:flex;gap:12px;flex-wrap:wrap;margin:24px 0}
.btn-light{background:white;color:var(--dark);border:1px solid #dce5d9}
.searchbox{background:white;padding:23px;border-radius:14px;box-shadow:0 12px 35px #173c2014;max-width:1100px;margin:25px auto 0}
.searchbox h2{font-size:20px;margin:0 0 16px}
.searchgrid{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:12px}
.field label{display:block;font-size:12px;font-weight:700;color:#52645a;margin-bottom:7px}
.field input,.field select{width:100%;min-width:0;padding:13px;border:1px solid #dce3dc;border-radius:7px;background:white;color:#263d31}
.searchgrid button{grid-column:1/-1;width:100%;padding:15px}
.trust{padding:22px 6%;display:flex;justify-content:center;gap:35px;flex-wrap:wrap;border-bottom:1px solid #edf0ea;font-size:13px;font-weight:700;color:#435b4d}
section{padding:62px 6%}
.sectionhead{display:flex;justify-content:space-between;align-items:end;gap:20px;flex-wrap:wrap}
h2{font-size:clamp(27px,4vw,38px);letter-spacing:-1px;margin:9px 0}
.intro{color:var(--muted);line-height:1.7;max-width:620px}
.grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:20px;margin-top:28px}
.vehicle{border:1px solid #e6eae3;border-radius:13px;overflow:hidden;background:white}
.vehicleart{height:170px;display:flex;align-items:center;justify-content:center;background:linear-gradient(135deg,#e2eee2,#f7f5e9);font-size:72px}
.vehiclebody{padding:19px}
.vehiclebody h3{margin:0 0 8px;font-size:20px}
.vehiclebody p{color:var(--muted);font-size:14px;line-height:1.6}
.tag{display:inline-block;font-size:11px;font-weight:800;letter-spacing:.5px;background:#edf5e7;color:#235c3e;padding:6px 9px;border-radius:20px}
.smallbtn{display:block;text-align:center;background:var(--dark);color:white;padding:12px;border-radius:7px;margin-top:15px;font-size:14px;font-weight:700}
.destinations{background:var(--cream)}
.destgrid{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:14px;margin-top:25px}
.dest{background:white;border:1px solid #e6eae3;padding:22px;border-radius:10px}
.dest strong{display:block;margin-bottom:5px}
.dest span{font-size:13px;color:var(--muted)}
.whygrid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:20px;margin-top:25px}
.why{padding:23px;border-radius:10px;background:#f5f7f1}
.why .symbol{font-size:27px}
.why h3{margin:10px 0}
.why p{font-size:14px;line-height:1.7;color:var(--muted)}
.partner{background:var(--dark);color:white;display:flex;justify-content:space-between;align-items:center;gap:30px;flex-wrap:wrap}
.partner p{color:#d0dfd5;line-height:1.7;max-width:600px}
.partner .btn{background:var(--lime);color:#193623}
.contact{text-align:center;background:#edf5e9}
.contact .intro{margin:10px auto 20px}
footer{background:#09271e;color:#d2e0d7;padding:35px 6%;display:flex;justify-content:space-between;gap:20px;flex-wrap:wrap;font-size:13px}
footer p{margin:5px 0}
@media(max-width:750px){
 .searchgrid{grid-template-columns:repeat(2,minmax(0,1fr))}
 .grid{grid-template-columns:1fr}
 .destgrid{grid-template-columns:repeat(2,minmax(0,1fr))}
 .whygrid{grid-template-columns:1fr}
 nav{gap:13px}
 .hero{padding-top:45px}
}
@media(max-width:420px){
 .searchgrid{grid-template-columns:1fr}
 .destgrid{grid-template-columns:1fr 1fr}
 .topbar{font-size:11px}
}
</style>
</head>
<body>
<div class="topbar">
<span>Electric travel, made simpler.</span>
<span>Kathmandu, Nepal · <a href="mailto:evgonep@gmail.com">evgonep@gmail.com</a></span>
</div>

<header>
<a class="logo" href="#home">EV GO <span>NEPAL.</span></a>
<nav>
<a href="#vehicles">Vehicles</a>
<a href="#destinations">Destinations</a>
<a href="#partner">For EV Owners</a>
<a href="#contact">Contact</a>
<a class="navbtn" href="#search">Find a Ride ↗</a>
</nav>
</header>

<main>
<section class="hero" id="home">
<div class="eyebrow">Your electric travel partner</div>
<h1>Find your ride.<br>Explore <span>Nepal.</span></h1>
<p class="lead">Discover electric vehicle options for city journeys, airport transfers and trips across Nepal. Tell us what you need, and we'll help you enquire about availability.</p>
<div class="hero-actions">
<a class="btn" href="#search">Find a Vehicle →</a>
<a class="btn btn-light" href="#partner">List Your EV</a>
</div>

<div class="searchbox" id="search">
<h2>Find a vehicle for your journey</h2>
<form id="searchForm">
<div class="searchgrid">
<div class="field">
<label for="pickup">Pickup location</label>
<select id="pickup" required>
<option value="">Choose location</option>
<option>Kathmandu</option>
<option>Bhaktapur</option>
<option>Lalitpur</option>
<option>Pokhara</option>
<option>Chitwan</option>
<option>Other location</option>
</select>
</div>
<div class="field">
<label for="type">Vehicle type</label>
<select id="type" required>
<option value="">Choose type</option>
<option>Any electric vehicle</option>
<option>Electric hatchback</option>
<option>Electric sedan</option>
<option>Electric SUV</option>
<option>Electric van</option>
</select>
</div>
<div class="field">
<label for="start">Pickup date</label>
<input id="start" type="date" required>
</div>
<div class="field">
<label for="end">Return date</label>
<input id="end" type="date" required>
</div>
<button class="btn" type="submit">Search & Enquire on WhatsApp →</button>
</div>
</form>
</div>
</section>

<div class="trust">
<span>✓ Direct booking enquiries</span>
<span>✓ Electric vehicle options</span>
<span>✓ Owner partnership enquiries</span>
</div>

<section id="vehicles">
<div class="sectionhead">
<div>
<div class="eyebrow">Explore our options</div>
<h2>Find the right EV for you</h2>
<p class="intro">Choose a vehicle category and ask us about available cars, rental rates and trip arrangements.</p>
</div>
</div>
<div class="grid">
<article class="vehicle">
<div class="vehicleart" aria-hidden="true">🚙</div>
<div class="vehiclebody">
<span class="tag">CITY TRAVEL</span>
<h3>Electric Hatchback</h3>
<p>A practical option for city rides, short journeys and everyday travel.</p>
<a class="smallbtn" href="https://wa.me/9779761118740?text=Hello%20EV%20Go%20Nepal%2C%20I%20want%20to%20enquire%20about%20an%20electric%20hatchback.">Enquire about this EV ↗</a>
</div>
</article>
<article class="vehicle">
<div class="vehicleart" aria-hidden="true">🚘</div>
<div class="vehiclebody">
<span class="tag">COMFORT</span>
<h3>Electric Sedan</h3>
<p>Ask about comfortable EV options for business travel and longer rides.</p>
<a class="smallbtn" href="https://wa.me/9779761118740?text=Hello%20EV%20Go%20Nepal%2C%20I%20want%20to%20enquire%20about%20an%20electric%20sedan.">Enquire about this EV ↗</a>
</div>
</article>
<article class="vehicle">
<div class="vehicleart" aria-hidden="true">🚗</div>
<div class="vehiclebody">
<span class="tag">EXTRA SPACE</span>
<h3>Electric SUV</h3>
<p>Explore available electric SUVs for family journeys and group travel.</p>
<a class="smallbtn" href="https://wa.me/9779761118740?text=Hello%20EV%20Go%20Nepal%2C%20I%20want%20to%20enquire%20about%20an%20electric%20SUV.">Enquire about this EV ↗</a>
</div>
</article>
</div>
<p class="intro">Vehicle categories are illustrative. Actual models, prices and availability must be confirmed before booking.</p>
</section>

<section class="destinations" id="destinations">
<div class="eyebrow">Where will you go?</div>
<h2>Start with your destination</h2>
<p class="intro">Tell us where your journey begins. We'll help you enquire about suitable electric vehicle options.</p>
<div class="destgrid">
<a class="dest" href="https://wa.me/9779761118740?text=I%20need%20an%20EV%20rental%20in%20Kathmandu."><strong>Kathmandu</strong><span>City rides ↗</span></a>
<a class="dest" href="https://wa.me/9779761118740?text=I%20need%20an%20EV%20rental%20in%20Bhaktapur."><strong>Bhaktapur</strong><span>Local travel ↗</span></a>
<a class="dest" href="https://wa.me/9779761118740?text=I%20need%20an%20EV%20rental%20in%20Pokhara."><strong>Pokhara</strong><span>Trip enquiries ↗</span></a>
<a class="dest" href="https://wa.me/9779761118740?text=I%20need%20an%20EV%20rental%20for%20a%20trip%20in%20Nepal."><strong>Across Nepal</strong><span>Plan a journey ↗</span></a>
</div>
</section>

<section id="about">
<div class="eyebrow">Why EV Go Nepal</div>
<h2>A simpler way to arrange your ride</h2>
<div class="whygrid">
<div class="why"><div class="symbol">⚡</div><h3>Electric-first</h3><p>Discover electric vehicle options for your next journey.</p></div>
<div class="why"><div class="symbol">💬</div><h3>Easy enquiries</h3><p>Contact us directly to discuss trip details, rates and availability.</p></div>
<div class="why"><div class="symbol">🤝</div><h3>Local partnerships</h3><p>We welcome EV owners interested in potential rental opportunities.</p></div>
</div>
</section>

<section class="partner" id="partner">
<div>
<div class="eyebrow" style="color:#c8f36a">For electric vehicle owners</div>
<h2>Have an EV? Let's work together.</h2>
<p>Connect with EV Go Nepal to discuss potential booking referrals and rental partnerships for your vehicle. All partnerships are subject to agreement and availability.</p>
</div>
<a class="btn" href="https://wa.me/9779761118740?text=Hello%20EV%20Go%20Nepal%2C%20I%20own%20an%20EV%20and%20would%20like%20to%20discuss%20a%20partnership.">Become a Partner ↗</a>
</section>

<section class="contact" id="contact">
<div class="eyebrow">Let's plan your journey</div>
<h2>Ready to find your EV?</h2>
<p class="intro">Contact us for vehicle enquiries, booking requests and partnership discussions.</p>
<a class="btn" href="https://wa.me/9779761118740?text=Hello%20EV%20Go%20Nepal%2C%20I%20would%20like%20to%20make%20an%20enquiry.">Chat on WhatsApp ↗</a>
<p><strong>WhatsApp:</strong> 9761118740</p>
<p><strong>Email:</strong> evgonep@gmail.com</p>
</section>
</main>

<footer>
<div><strong>EV GO NEPAL.</strong><p>Electric journeys, made simpler.</p></div>
<div><p>WhatsApp: 9761118740</p><p>Email: evgonep@gmail.com</p></div>
<p>© 2026 EV Go Nepal</p>
</footer>

<script>
document.getElementById('searchForm').addEventListener('submit',function(e){
e.preventDefault();
const pickup=document.getElementById('pickup').value;
const type=document.getElementById('type').value;
const start=document.getElementById('start').value;
const end=document.getElementById('end').value;
if(end<start){alert('Return date must be on or after the pickup date.');return;}
const message='Hello EV Go Nepal! I would like to enquire about a rental. Pickup location: '+pickup+'. Vehicle type: '+type+'. Pickup date: '+start+'. Return date: '+end+'. Please confirm availability and price.';
window.open('https://wa.me/9779761118740?text='+encodeURIComponent(message),'_blank');
});
</script>
</body>
</html>
