
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#09221b">
  <meta name="description" content="Find electric car rental options in Nepal with EV Go Nepal.">
  <title>EV Go Nepal | Easy EV Rental</title>

  <style>
    :root {
      --green: #c5f477;
      --dark: #09221b;
      --light: #f5f7f1;
      --text: #17251e;
      --muted: #66736b;
      --white: #fff;
      --border: #e2e8df;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; scroll-padding-top: 75px; }

    body {
      font-family: Arial, Helvetica, sans-serif;
      color: var(--text);
      background: var(--light);
      line-height: 1.55;
    }

    a { color: inherit; text-decoration: none; }

    button, input, select, textarea { font: inherit; }

    .container { width: min(1050px, 92%); margin: auto; }

    .header {
      background: var(--dark);
      color: white;
      position: sticky;
      top: 0;
      z-index: 20;
    }

    .nav {
      min-height: 68px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 12px;
    }

    .logo {
      font-size: 1.1rem;
      font-weight: 900;
      white-space: nowrap;
    }

    .logo span { color: var(--green); }

    .nav-links {
      display: flex;
      align-items: center;
      gap: 20px;
      font-size: .88rem;
    }

    .nav-links a:hover { color: var(--green); }

    .button {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      border: 0;
      border-radius: 12px;
      padding: 13px 18px;
      min-height: 46px;
      font-weight: 800;
      cursor: pointer;
      text-align: center;
    }

    .button-green { background: var(--green); color: var(--dark); }
    .button-dark { background: var(--dark); color: white; }
    .button-white { background: white; color: var(--dark); }

    .button:active { transform: scale(.98); }

    .hero {
      background:
        radial-gradient(circle at 85% 20%, rgba(197,244,119,.15), transparent 32%),
        var(--dark);
      color: white;
      padding: 48px 0 35px;
    }

    .hero-grid {
      display: grid;
      grid-template-columns: 1.1fr .9fr;
      align-items: center;
      gap: 28px;
    }

    .eyebrow {
      color: #669d32;
      text-transform: uppercase;
      font-size: .76rem;
      font-weight: 900;
      letter-spacing: 1.5px;
      margin-bottom: 10px;
    }

    .hero .eyebrow { color: var(--green); }

    h1 {
      font-size: clamp(2.5rem, 6vw, 4.5rem);
      line-height: 1.06;
      letter-spacing: -2px;
    }

    h1 span { color: var(--green); }

    .hero p {
      color: #c7d4cc;
      margin: 17px 0 22px;
      max-width: 480px;
    }

    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .hero-car {
      min-height: 235px;
      border-radius: 24px;
      display: grid;
      place-items: center;
      overflow: hidden;
      background: linear-gradient(140deg, #1a3c2e, #102b21);
      border: 1px solid rgba(255,255,255,.12);
    }

    .hero-car img {
      width: 100%;
      height: 260px;
      padding: 15px;
      object-fit: contain;
    }

    .hero-fallback {
      text-align: center;
      padding: 24px;
      color: #dbe8dc;
    }

    .hero-fallback .symbol { font-size: 5rem; }

    /* Quick booking */

    .quick-booking {
      margin-top: -2px;
      padding: 25px 0;
      background: white;
      border-bottom: 1px solid var(--border);
    }

    .quick-box {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
    }

    .quick-box h2 { font-size: 1.35rem; }

    .quick-box p {
      color: var(--muted);
      font-size: .88rem;
      margin-top: 4px;
    }

    .section { padding: 58px 0; }

    .section-title {
      font-size: clamp(1.8rem, 4vw, 2.5rem);
      letter-spacing: -1px;
    }

    .section-description {
      color: var(--muted);
      margin-top: 9px;
      max-width: 590px;
    }

    /* Cars */

    .cars {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 18px;
      margin-top: 25px;
    }

    .car-card {
      background: white;
      border: 1px solid var(--border);
      border-radius: 18px;
      overflow: hidden;
      min-width: 0;
    }

    .car-photo {
      height: 185px;
      background: #e9eee5;
      display: grid;
      place-items: center;
      overflow: hidden;
    }

    .car-photo img {
      width: 100%;
      height: 100%;
      padding: 12px;
      object-fit: contain;
    }

    .car-fallback {
      text-align: center;
      padding: 15px;
      color: #526354;
    }

    .car-fallback .symbol { font-size: 3.5rem; }

    .car-info { padding: 17px; }

    .car-info h3 { font-size: 1.1rem; }

    .car-info p {
      font-size: .85rem;
      color: var(--muted);
      margin-top: 4px;
    }

    .car-meta {
      display: flex;
      flex-wrap: wrap;
      gap: 7px;
      margin: 13px 0;
    }

    .car-meta span {
      background: #f0f5eb;
      color: #435644;
      padding: 5px 8px;
      border-radius: 7px;
      font-size: .73rem;
    }

    .car-info .button { width: 100%; }

    .note {
      font-size: .8rem;
      color: var(--muted);
      margin-top: 17px;
    }

    /* Booking */

    .booking {
      background: #eaf0e4;
    }

    .booking-layout {
      display: grid;
      grid-template-columns: .8fr 1.2fr;
      align-items: start;
      gap: 28px;
    }

    .booking-info h2 {
      font-size: clamp(2rem, 4vw, 2.8rem);
      line-height: 1.15;
    }

    .booking-info > p {
      color: var(--muted);
      margin-top: 13px;
    }

    .contact-card {
      margin-top: 20px;
      padding: 18px;
      background: white;
      border: 1px solid var(--border);
      border-radius: 15px;
      overflow-wrap: anywhere;
    }

    .contact-card p {
      color: var(--muted);
      font-size: .8rem;
    }

    .contact-card strong {
      display: block;
      margin: 4px 0 12px;
    }

    .form-card {
      background: white;
      padding: 23px;
      border: 1px solid var(--border);
      border-radius: 20px;
    }

    .form-card h3 { font-size: 1.3rem; }

    .form-intro {
      color: var(--muted);
      font-size: .84rem;
      margin: 6px 0 19px;
    }

    .field { margin-bottom: 14px; }

    .field label {
      display: block;
      font-weight: 800;
      font-size: .84rem;
      margin-bottom: 6px;
    }

    .field input,
    .field select,
    .field textarea {
      width: 100%;
      padding: 12px;
      border: 1px solid #d9e1d6;
      border-radius: 10px;
      background: #fcfdfb;
      color: var(--text);
      min-height: 46px;
    }

    .field textarea {
      min-height: 80px;
      resize: vertical;
    }

    .field input:focus,
    .field select:focus,
    .field textarea:focus {
      outline: 2px solid #a9df70;
      border-color: transparent;
    }

    .form-card .button { width: 100%; }

    .form-note {
      text-align: center;
      color: var(--muted);
      font-size: .74rem;
      margin-top: 10px;
    }

    /* Three simple points */

    .why-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 17px;
      margin-top: 23px;
    }

    .why-card {
      padding: 21px;
      background: white;
      border: 1px solid var(--border);
      border-radius: 16px;
    }

    .why-icon { font-size: 1.8rem; }

    .why-card h3 {
      margin-top: 10px;
      font-size: 1.05rem;
    }

    .why-card p {
      color: var(--muted);
      font-size: .85rem;
      margin-top: 7px;
    }

    /* Owners */

    .owners {
      background: var(--dark);
      color: white;
      padding: 38px 0;
    }

    .owners-inner {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 25px;
    }

    .owners h2 {
      font-size: clamp(1.6rem, 4vw, 2.3rem);
    }

    .owners p {
      color: #bdcec2;
      margin-top: 8px;
      max-width: 570px;
    }

    /* Footer */

    footer {
      background: #061711;
      color: white;
      padding: 27px 0;
    }

    .footer-inner {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 15px;
      flex-wrap: wrap;
    }

    footer p {
      color: #afbeb4;
      font-size: .82rem;
    }

    .footer-links {
      display: flex;
      flex-wrap: wrap;
      gap: 17px;
      font-size: .84rem;
    }

    .whatsapp {
      position: fixed;
      right: 16px;
      bottom: 16px;
      z-index: 30;
      background: #25d366;
      color: white;
      border-radius: 50px;
      padding: 14px 17px;
      font-weight: 900;
      box-shadow: 0 4px 20px #0003;
    }

    @media (max-width: 760px) {
      .nav { min-height: 62px; }

      .nav-links {
        display: none;
        position: absolute;
        top: 62px;
        left: 0;
        right: 0;
        background: var(--dark);
        padding: 12px 4% 20px;
      }

      .nav-links.open {
        display: grid;
        gap: 0;
      }

      .nav-links a {
        padding: 12px 0;
        border-bottom: 1px solid #ffffff15;
      }

      .nav .button { padding: 10px 12px; font-size: .78rem; }

      .hero { padding: 35px 0 25px; }

      .hero-grid { grid-template-columns: 1fr; gap: 22px; }

      .hero-car { min-height: 190px; }
      .hero-car img { height: 210px; }

      .quick-box { align-items: stretch; flex-direction: column; gap: 13px; }

      .quick-box .button { width: 100%; }

      .section { padding: 43px 0; }

      .cars { grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 12px; }

      .car-photo { height: 145px; }

      .car-info { padding: 12px; }

      .car-info h3 { font-size: .98rem; }

      .car-meta { gap: 5px; }

      .car-meta span { font-size: .68rem; }

      .car-info .button { font-size: .8rem; padding: 10px 7px; }

      .booking-layout { grid-template-columns: 1fr; }

      .why-grid { grid-template-columns: 1fr; }

      .owners-inner { align-items: stretch; flex-direction: column; }

      .owners-inner .button { width: 100%; }

      .footer-inner { align-items: flex-start; flex-direction: column; }
    }

    @media (max-width: 390px) {
      .cars { grid-template-columns: 1fr; }
      .car-photo { height: 210px; }
    }
  </style>
</head>

<body>

<header class="header">
  <div class="container nav">
    <a href="#home" class="logo">⚡ EV GO <span>NEPAL</span></a>

    <nav class="nav-links" id="navLinks" aria-label="Main navigation">
      <a href="#cars">Our Cars</a>
      <a href="#booking">Book a Car</a>
      <a href="#owners">For EV Owners</a>
      <a href="#contact">Contact</a>
    </nav>

    <a class="button button-green"
       href="https://wa.me/9779761118740?text=Hello%20EV%20Go%20Nepal%2C%20I%20want%20to%20enquire%20about%20an%20EV%20rental."
       target="_blank" rel="noopener">WhatsApp ↗</a>
  </div>
</header>

<main>
  <section class="hero" id="home">
    <div class="container hero-grid">
      <div>
        <div class="eyebrow">Electric travel made simple</div>
        <h1>Find your EV.<br><span>Plan your trip.</span></h1>
        <p>
          Looking for an electric car in Nepal? Choose a vehicle,
          tell us your travel plans and send your enquiry directly
          through WhatsApp.
        </p>
        <div class="hero-actions">
          <a class="button button-green" href="#booking">Book an EV ↓</a>
          <a class="button button-white" href="#cars">View Cars</a>
        </div>
      </div>

      <div class="hero-car">
        <img src="images/hero-ev.jpg" alt="Electric car"
          onerror="this.hidden=true;this.nextElementSibling.hidden=false;">
        <div class="hero-fallback" hidden>
          <div class="symbol">🚙</div>
          <strong>Welcome to EV Go Nepal</strong>
          <p>Add your car photo as images/hero-ev.jpg</p>
        </div>
      </div>
    </div>
  </section>

  <section class="quick-booking">
    <div class="container quick-box">
      <div>
        <h2>Need a car for your next trip?</h2>
        <p>Choose a car below or send a quick booking enquiry.</p>
      </div>
      <a class="button button-dark" href="#booking">Start Booking →</a>
    </div>
  </section>

  <section class="section" id="cars">
    <div class="container">
      <div class="eyebrow">Choose your vehicle</div>
      <h2 class="section-title">Explore our EV options</h2>
      <p class="section-description">
        Choose a model to start an enquiry. We will need to confirm
        the actual vehicle, availability and rental price.
      </p>

      <div class="cars">

        <article class="car-card">
          <div class="car-photo">
            <img src="images/byd-atto-2.jpg" alt="BYD Atto 2"
              loading="lazy"
              onerror="this.hidden=true;this.nextElementSibling.hidden=false;">
            <div class="car-fallback" hidden>
              <div class="symbol">🚙</div>
              <strong>BYD Atto 2</strong>
              <p>Add images/byd-atto-2.jpg</p>
            </div>
          </div>
          <div class="car-info">
            <h3>BYD Atto 2</h3>
            <p>Compact electric SUV</p>
            <div class="car-meta"><span>⚡ Electric</span><span>🚙 SUV</span></div>
            <a class="button button-dark choose-car" href="#booking" data-car="BYD Atto 2">Choose This Car</a>
          </div>
        </article>

        <article class="car-card">
          <div class="car-photo">
            <img src="images/tata-nexon-ev.jpg" alt="Tata Nexon EV"
              loading="lazy"
              onerror="this.hidden=true;this.nextElementSibling.hidden=false;">
            <div class="car-fallback" hidden>
              <div class="symbol">🚙</div>
              <strong>Tata Nexon EV</strong>
              <p>Add images/tata-nexon-ev.jpg</p>
            </div>
          </div>
          <div class="car-info">
            <h3>Tata Nexon EV</h3>
            <p>Electric SUV</p>
            <div class="car-meta"><span>⚡ Electric</span><span>🚙 SUV</span></div>
            <a class="button button-dark choose-car" href="#booking" data-car="Tata Nexon EV">Choose This Car</a>
          </div>
        </article>

        <article class="car-card">
          <div class="car-photo">
            <img src="images/byd-dolphin.jpg" alt="BYD Dolphin"
              loading="lazy"
              onerror="this.hidden=true;this.nextElementSibling.hidden=false;">
            <div class="car-fallback" hidden>
              <div class="symbol">🚗</div>
              <strong>BYD Dolphin</strong>
              <p>Add images/byd-dolphin.jpg</p>
            </div>
          </div>
          <div class="car-info">
            <h3>BYD Dolphin</h3>
            <p>Electric hatchback</p>
            <div class="car-meta"><span>⚡ Electric</span><span>🚗 Compact</span></div>
            <a class="button button-dark choose-car" href="#booking" data-car="BYD Dolphin">Choose This Car</a>
          </div>
        </article>

        <article class="car-card">
          <div class="car-photo">
            <img src="images/mg-zs-ev.jpg" alt="MG ZS EV"
              loading="lazy"
              onerror="this.hidden=true;this.nextElementSibling.hidden=false;">
            <div class="car-fallback" hidden>
              <div class="symbol">🚙</div>
              <strong>MG ZS EV</strong>
              <p>Add images/mg-zs-ev.jpg</p>
            </div>
          </div>
          <div class="car-info">
            <h3>MG ZS EV</h3>
            <p>Electric SUV</p>
            <div class="car-meta"><span>⚡ Electric</span><span>🚙 SUV</span></div>
            <a class="button button-dark choose-car" href="#booking" data-car="MG ZS EV">Choose This Car</a>
          </div>
        </article>

        <article class="car-card">
          <div class="car-photo">
            <img src="images/tata-tiago-ev.jpg" alt="Tata Tiago EV"
              loading="lazy"
              onerror="this.hidden=true;this.nextElementSibling.hidden=false;">
            <div class="car-fallback" hidden>
              <div class="symbol">🚗</div>
              <strong>Tata Tiago EV</strong>
              <p>Add images/tata-tiago-ev.jpg</p>
            </div>
          </div>
          <div class="car-info">
            <h3>Tata Tiago EV</h3>
            <p>Compact electric hatchback</p>
            <div class="car-meta"><span>⚡ Electric</span><span>🏙️ City</span></div>
            <a class="button button-dark choose-car" href="#booking" data-car="Tata Tiago EV">Choose This Car</a>
          </div>
        </article>

        <article class="car-card">
          <div class="car-photo">
            <img src="images/byd-atto-3.jpg" alt="BYD Atto 3"
              loading="lazy"
              onerror="this.hidden=true;this.nextElementSibling.hidden=false;">
            <div class="car-fallback" hidden>
              <div class="symbol">🚙</div>
              <strong>BYD Atto 3</strong>
              <p>Add images/byd-atto-3.jpg</p>
            </div>
          </div>
          <div class="car-info">
            <h3>BYD Atto 3</h3>
            <p>Electric SUV</p>
            <div class="car-meta"><span>⚡ Electric</span><span>🛣️ Travel</span></div>
            <a class="button button-dark choose-car" href="#booking" data-car="BYD Atto 3">Choose This Car</a>
          </div>
        </article>

      </div>

      <p class="note">
        These are example models, not a confirmed inventory. Ask us to
        confirm the exact vehicle, availability and price before booking.
      </p>
    </div>
  </section>

  <section class="section booking" id="booking">
    <div class="container booking-layout">
      <div class="booking-info">
        <div class="eyebrow">Quick booking</div>
        <h2>Book your car in a few easy steps.</h2>
        <p>
          Enter just the essential details. Your enquiry will open in
          WhatsApp so you can send it directly to EV Go Nepal.
        </p>

        <div class="contact-card" id="contact">
          <p>Call or WhatsApp</p>
          <strong>9761118740</strong>
          <a class="button button-green"
             href="https://wa.me/9779761118740"
             target="_blank" rel="noopener">Chat With Us ↗</a>
          <p style="margin-top:16px">Email</p>
          <strong>evgonep@gmail.com</strong>
          <a href="mailto:evgonep@gmail.com">Send an email</a>
        </div>
      </div>

      <form class="form-card" id="bookingForm">
        <h3>Rental enquiry</h3>
        <p class="form-intro">Fields marked * are required.</p>

        <div class="field">
          <label for="name">Your name *</label>
          <input id="name" name="name" required
            placeholder="Enter your name" autocomplete="name">
        </div>

        <div class="field">
          <label for="phone">Your phone number *</label>
          <input id="phone" name="phone" type="tel" required
            placeholder="Enter your phone number" autocomplete="tel">
        </div>

        <div class="field">
          <label for="car">Choose your car *</label>
          <select id="car" name="car" required>
            <option value="">Select a vehicle</option>
            <option>BYD Atto 2</option>
            <option>Tata Nexon EV</option>
            <option>BYD Dolphin</option>
            <option>MG ZS EV</option>
            <option>Tata Tiago EV</option>
            <option>BYD Atto 3</option>
            <option>Any available EV</option>
          </select>
        </div>

        <div class="field">
          <label for="type">What do you need? *</label>
          <select id="type" name="type" required>
            <option value="">Choose an option</option>
            <option>Car with driver</option>
            <option>Self-drive rental</option>
            <option>Airport pickup or drop-off</option>
            <option>Long-distance trip</option>
            <option>Other</option>
          </select>
        </div>

        <div class="field">
          <label for="destination">Where are you going?</label>
          <input id="destination" name="destination"
            placeholder="e.g. Kathmandu to Pokhara">
        </div>

        <div class="field">
          <label for="date">Travel date</label>
          <input id="date" name="date" type="date">
        </div>

        <button class="button button-green" type="submit">
          Send Booking Enquiry on WhatsApp →
        </button>

        <p class="form-note">
          This sends an enquiry only. Your booking is confirmed after
          availability and price are agreed.
        </p>
      </form>
    </div>
  </section>

  <section class="section">
    <div class="container">
      <div class="eyebrow">Why EV Go Nepal?</div>
      <h2 class="section-title">Easy from start to finish.</h2>

      <div class="why-grid">
        <article class="why-card">
          <div class="why-icon">🚘</div>
          <h3>Choose a car</h3>
          <p>Browse the options and select the model you prefer.</p>
        </article>
        <article class="why-card">
          <div class="why-icon">💬</div>
          <h3>Ask for a price</h3>
          <p>Discuss availability and the final rental cost directly.</p>
        </article>
        <article class="why-card">
          <div class="why-icon">📍</div>
          <h3>Plan your journey</h3>
          <p>Share your destination and travel requirements.</p>
        </article>
      </div>
    </div>
  </section>

  <section class="owners" id="owners">
    <div class="container owners-inner">
      <div>
        <h2>Own an electric car?</h2>
        <p>
          Interested in listing your EV or discussing a rental partnership?
          Contact us to talk about possible arrangements.
        </p>
      </div>
      <a class="button button-green"
         href="https://wa.me/9779761118740?text=Hello%20EV%20Go%20Nepal%2C%20I%20own%20an%20EV%20and%20would%20like%20to%20discuss%20a%20partnership."
         target="_blank" rel="noopener">Partner With Us ↗</a>
    </div>
  </section>
</main>

<footer>
  <div class="container footer-inner">
    <div>
      <div class="logo">⚡ EV GO <span>NEPAL</span></div>
      <p>Electric travel made simple.</p>
      <p>© <span id="year"></span> EV Go Nepal</p>
    </div>

    <div class="footer-links">
      <a href="#home">Home</a>
      <a href="#cars">Our Cars</a>
      <a href="#booking">Book</a>
      <a href="#owners">EV Owners</a>
      <a href="mailto:evgonep@gmail.com">Email</a>
    </div>
  </div>
</footer>

<a class="whatsapp"
   href="https://wa.me/9779761118740?text=Hello%20EV%20Go%20Nepal%2C%20I%20want%20to%20ask%20about%20EV%20rental."
   target="_blank" rel="noopener" aria-label="WhatsApp EV Go Nepal">
  WhatsApp ☎
</a>

<script>
  // Add mobile navigation button
  const nav = document.querySelector(".nav");
  const links = document.getElementById("navLinks");
  const menuButton = document.createElement("button");

  menuButton.type = "button";
  menuButton.textContent = "☰";
  menuButton.setAttribute("aria-label", "Open menu");
  menuButton.setAttribute("aria-expanded", "false");

  menuButton.style.cssText =
    "display:none;background:none;border:0;color:white;font-size:1.7rem;cursor:pointer";

  nav.insertBefore(menuButton, links);

  function updateMenuButton() {
    menuButton.style.display = window.innerWidth <= 760 ? "block" : "none";
    if (window.innerWidth > 760) {
      links.classList.remove("open");
      menuButton.setAttribute("aria-expanded", "false");
      menuButton.textContent = "☰";
    }
  }

  updateMenuButton();
  window.addEventListener("resize", updateMenuButton);

  menuButton.addEventListener("click", function () {
    const open = links.classList.toggle("open");
    menuButton.textContent = open ? "×" : "☰";
    menuButton.setAttribute("aria-expanded", String(open));
  });

  links.querySelectorAll("a").forEach(function (link) {
    link.addEventListener("click", function () {
      links.classList.remove("open");
      menuButton.textContent = "☰";
      menuButton.setAttribute("aria-expanded", "false");
    });
  });

  // Select a car automatically when its button is pressed
  document.querySelectorAll(".choose-car").forEach(function (link) {
    link.addEventListener("click", function () {
      document.getElementById("car").value = link.dataset.car;
    });
  });

  // Use today's date as the earliest date
  const dateInput = document.getElementById("date");
  const today = new Date();
  dateInput.min = [
    today.getFullYear(),
    String(today.getMonth() + 1).padStart(2, "0"),
    String(today.getDate()).padStart(2, "0")
  ].join("-");

  document.getElementById("year").textContent = new Date().getFullYear();

  // Send the booking enquiry to WhatsApp
  document.getElementById("bookingForm").addEventListener("submit", function (event) {
    event.preventDefault();

    const name = document.getElementById("name").value.trim();
    const phone = document.getElementById("phone").value.trim();
    const car = document.getElementById("car").value;
    const type = document.getElementById("type").value;
    const destination = document.getElementById("destination").value.trim() || "Not specified";
    const date = document.getElementById("date").value || "Not specified";

    const message =
      "Hello EV Go Nepal! I would like to enquire about a rental.\n\n" +
      "Name: " + name + "\n" +
      "Phone: " + phone + "\n" +
      "Preferred car: " + car + "\n" +
      "Rental type: " + type + "\n" +
      "Destination: " + destination + "\n" +
      "Travel date: " + date + "\n\n" +
      "Please let me know availability and price.";

    const url = "https://wa.me/9779761118740?text=" +
      encodeURIComponent(message);

    window.location.href = url;
  });
</script>

</body>
</html>

