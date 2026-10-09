
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#071a17">
  <meta name="description" content="Book electric cars for travel, airport transfers, business trips and private journeys across Nepal with EV Go Nepal.">
  <title>EV Go Nepal | Premium Electric Car Rentals</title>

  <style>
    :root {
      --dark: #071a17;
      --dark2: #102a24;
      --green: #b8f36b;
      --green2: #8bd943;
      --cream: #f6f7f1;
      --white: #ffffff;
      --muted: #a8b7b0;
      --text: #18251f;
      --border: #e2e8e1;
      --radius: 22px;
      --shadow: 0 15px 45px rgba(5, 25, 18, .09);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
      scroll-padding-top: 85px;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: var(--cream);
      color: var(--text);
      line-height: 1.6;
      overflow-x: hidden;
    }

    img {
      display: block;
      max-width: 100%;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    button, input, select, textarea {
      font: inherit;
    }

    button, a {
      -webkit-tap-highlight-color: transparent;
    }

    .container {
      width: min(1160px, 91%);
      margin: 0 auto;
    }

    .section {
      padding: 88px 0;
    }

    .section-heading {
      max-width: 680px;
      margin-bottom: 36px;
    }

    .eyebrow {
      color: #548c26;
      font-size: .76rem;
      font-weight: 800;
      text-transform: uppercase;
      letter-spacing: 2px;
      margin-bottom: 12px;
    }

    h1, h2, h3 {
      line-height: 1.15;
      letter-spacing: -1px;
    }

    h1 {
      font-size: clamp(2.6rem, 6vw, 5rem);
    }

    h2 {
      font-size: clamp(2rem, 4vw, 3.2rem);
    }

    h3 {
      font-size: 1.25rem;
    }

    .section-heading p {
      color: #67736c;
      margin-top: 14px;
      max-width: 580px;
    }

    .btn {
      min-height: 49px;
      padding: 13px 21px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 9px;
      border-radius: 999px;
      font-weight: 800;
      font-size: .92rem;
      border: 1px solid transparent;
      cursor: pointer;
      transition: transform .2s, background .2s;
    }

    .btn:hover {
      transform: translateY(-2px);
    }

    .btn-green {
      background: var(--green);
      color: var(--dark);
    }

    .btn-green:hover {
      background: #a6e957;
    }

    .btn-outline {
      color: white;
      border-color: rgba(255,255,255,.35);
      background: transparent;
    }

    .btn-dark {
      background: var(--dark);
      color: white;
    }

    /* NAVIGATION */

    .navbar {
      position: sticky;
      top: 0;
      z-index: 100;
      background: rgba(7, 26, 23, .97);
      color: white;
      border-bottom: 1px solid rgba(255,255,255,.08);
      backdrop-filter: blur(15px);
    }

    .nav-inner {
      min-height: 76px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
    }

    .brand {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      font-weight: 900;
      font-size: 1.25rem;
      letter-spacing: -.5px;
      white-space: nowrap;
    }

    .brand-icon {
      width: 41px;
      height: 41px;
      display: grid;
      place-items: center;
      border-radius: 13px;
      background: var(--green);
      color: var(--dark);
      font-size: 1.3rem;
    }

    .brand small {
      display: block;
      font-size: .61rem;
      color: var(--muted);
      letter-spacing: 2.1px;
      font-weight: 600;
      margin-top: -3px;
    }

    .nav-links {
      display: flex;
      align-items: center;
      gap: 25px;
      font-size: .9rem;
      color: #e0e9e3;
    }

    .nav-links a:hover {
      color: var(--green);
    }

    .menu-toggle {
      display: none;
      border: 0;
      background: transparent;
      color: white;
      font-size: 1.8rem;
      cursor: pointer;
    }

    /* HERO */

    .hero {
      position: relative;
      overflow: hidden;
      color: white;
      background:
        radial-gradient(ellipse at 82% 30%, rgba(105, 160, 85, .2), transparent 38%),
        linear-gradient(130deg, #071a17, #102c24 75%, #18392b);
      padding: 76px 0 70px;
    }

    .hero::before {
      content: "";
      position: absolute;
      width: 480px;
      height: 480px;
      right: -170px;
      top: -200px;
      border: 1px solid rgba(184,243,107,.16);
      border-radius: 50%;
      box-shadow:
        0 0 0 45px rgba(184,243,107,.025),
        0 0 0 90px rgba(184,243,107,.025);
      pointer-events: none;
    }

    .hero-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      align-items: center;
      gap: 42px;
      position: relative;
      z-index: 1;
    }

    .hero-copy .eyebrow {
      color: var(--green);
    }

    .hero-copy h1 span {
      color: var(--green);
    }

    .hero-copy > p {
      max-width: 510px;
      margin: 22px 0 28px;
      color: #c1d0c8;
      font-size: 1.04rem;
    }

    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .hero-note {
      margin-top: 25px;
      color: #aabdb3;
      font-size: .85rem;
    }

    .hero-visual {
      min-width: 0;
      position: relative;
    }

    .hero-photo {
      position: relative;
      min-height: 350px;
      height: 100%;
      display: grid;
      place-items: center;
      overflow: hidden;
      border-radius: 30px;
      background:
        radial-gradient(ellipse at center, rgba(184,243,107,.13), transparent 60%),
        linear-gradient(145deg, #1b3b30, #0b211c);
      border: 1px solid rgba(255,255,255,.12);
    }

    .hero-photo img {
      width: 100%;
      height: 350px;
      object-fit: contain;
      object-position: center;
      padding: 20px;
    }

    .hero-fallback {
      padding: 25px;
      text-align: center;
      color: #d9e6dc;
    }

    .hero-fallback .car-symbol {
      font-size: 6rem;
      line-height: 1.2;
    }

    .hero-fallback p {
      color: #a9c0b3;
      font-size: .85rem;
      margin-top: 8px;
    }

    .hero-tag {
      position: absolute;
      bottom: 18px;
      left: 18px;
      background: rgba(7,26,23,.9);
      border: 1px solid rgba(255,255,255,.12);
      padding: 12px 16px;
      border-radius: 15px;
      font-size: .85rem;
    }

    .hero-tag strong {
      display: block;
      color: var(--green);
    }

    .hero-tag span {
      color: #d2ded7;
      font-size: .75rem;
    }

    .trust-row {
      display: flex;
      flex-wrap: wrap;
      gap: 25px;
      margin-top: 27px;
      color: #d7e3da;
      font-size: .83rem;
    }

    .trust-row span::before {
      content: "✓";
      color: var(--green);
      font-weight: 900;
      margin-right: 7px;
    }

    /* QUICK STRIP */

    .quick-strip {
      background: white;
      border-bottom: 1px solid var(--border);
    }

    .quick-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
    }

    .quick-item {
      padding: 24px 20px;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 13px;
      border-right: 1px solid var(--border);
    }

    .quick-item:last-child {
      border-right: 0;
    }

    .quick-icon {
      width: 45px;
      height: 45px;
      display: grid;
      place-items: center;
      background: #eef8e6;
      border-radius: 14px;
      font-size: 1.25rem;
      flex-shrink: 0;
    }

    .quick-item strong {
      display: block;
      font-size: .94rem;
    }

    .quick-item small {
      color: #758078;
      font-size: .78rem;
    }

    /* CARS */

    .fleet-section {
      background: var(--cream);
    }

    .fleet-top {
      display: flex;
      align-items: end;
      justify-content: space-between;
      gap: 20px;
    }

    .fleet-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 23px;
    }

    .car-card {
      min-width: 0;
      background: white;
      border: 1px solid #e7ebe4;
      border-radius: var(--radius);
      overflow: hidden;
      box-shadow: 0 5px 18px rgba(8,28,20,.035);
      transition: transform .25s, box-shadow .25s;
    }

    .car-card:hover {
      transform: translateY(-5px);
      box-shadow: var(--shadow);
    }

    .car-image {
      height: 225px;
      position: relative;
      display: grid;
      place-items: center;
      overflow: hidden;
      background:
        radial-gradient(ellipse at 50% 65%, rgba(129,178,97,.14), transparent 65%),
        linear-gradient(145deg, #f1f4ed, #e7ece4);
    }

    .car-image img {
      width: 100%;
      height: 100%;
      padding: 15px;
      object-fit: contain;
      object-position: center;
      transition: transform .35s;
    }

    .car-card:hover .car-image img {
      transform: scale(1.035);
    }

    .car-placeholder {
      padding: 20px;
      text-align: center;
      color: #66766a;
    }

    .car-placeholder .car-symbol {
      font-size: 4.5rem;
      line-height: 1.2;
    }

    .car-placeholder p {
      font-size: .77rem;
      margin-top: 5px;
    }

    .car-label {
      position: absolute;
      top: 13px;
      left: 13px;
      z-index: 1;
      padding: 6px 10px;
      background: var(--dark);
      color: white;
      border-radius: 999px;
      font-size: .67rem;
      font-weight: 800;
      letter-spacing: .2px;
    }

    .car-content {
      padding: 20px;
    }

    .car-content h3 {
      margin-bottom: 5px;
    }

    .car-type {
      color: #748078;
      font-size: .81rem;
    }

    .car-specs {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      padding: 16px 0;
      margin: 13px 0;
      border-top: 1px solid #edf0eb;
      border-bottom: 1px solid #edf0eb;
    }

    .car-specs span {
      background: #f1f5ee;
      padding: 6px 9px;
      border-radius: 8px;
      font-size: .73rem;
      color: #405347;
    }

    .car-bottom {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 10px;
    }

    .price-label {
      font-size: .72rem;
      color: #7a847c;
    }

    .price-value {
      display: block;
      font-size: .9rem;
      font-weight: 800;
    }

    .car-bottom .btn {
      min-height: 42px;
      padding: 10px 14px;
      font-size: .8rem;
    }

    .fleet-note {
      margin-top: 22px;
      color: #6c786f;
      font-size: .82rem;
    }

    /* SERVICES */

    .services-section {
      background: white;
    }

    .services-grid {
      display: grid;
      grid-template-columns: repeat(4, minmax(0, 1fr));
      gap: 17px;
    }

    .service-card {
      border: 1px solid var(--border);
      border-radius: 19px;
      padding: 25px 21px;
      transition: background .2s, transform .2s;
    }

    .service-card:hover {
      background: #f5faef;
      transform: translateY(-3px);
    }

    .service-icon {
      width: 53px;
      height: 53px;
      display: grid;
      place-items: center;
      background: #eef8e6;
      border-radius: 16px;
      font-size: 1.55rem;
      margin-bottom: 20px;
    }

    .service-card p {
      margin-top: 10px;
      color: #728077;
      font-size: .86rem;
    }

    /* HOW IT WORKS */

    .steps-section {
      background: #eef2e9;
    }

    .steps-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 25px;
    }

    .step-card {
      position: relative;
      padding: 28px;
      border-radius: 20px;
      background: white;
      border: 1px solid #e2e8df;
    }

    .step-number {
      width: 46px;
      height: 46px;
      display: grid;
      place-items: center;
      border-radius: 15px;
      background: var(--green);
      color: var(--dark);
      font-size: 1.2rem;
      font-weight: 900;
      margin-bottom: 20px;
    }

    .step-card p {
      margin-top: 10px;
      color: #6c786f;
      font-size: .9rem;
    }

    /* PARTNERS */

    .partner-section {
      background: var(--dark);
      color: white;
      overflow: hidden;
    }

    .partner-grid {
      display: grid;
      grid-template-columns: 1fr .9fr;
      align-items: center;
      gap: 50px;
    }

    .partner-section .eyebrow {
      color: var(--green);
    }

    .partner-section p {
      margin-top: 18px;
      color: #bac9c0;
    }

    .partner-list {
      list-style: none;
      margin: 24px 0 28px;
    }

    .partner-list li {
      margin: 10px 0;
      color: #e0e9e3;
    }

    .partner-list li::before {
      content: "✓";
      color: var(--green);
      margin-right: 10px;
      font-weight: 900;
    }

    .partner-panel {
      padding: 30px;
      border: 1px solid rgba(255,255,255,.12);
      border-radius: 25px;
      background:
        radial-gradient(circle at 100% 0%, rgba(184,243,107,.1), transparent 50%),
        #102820;
    }

    .partner-panel h3 {
      font-size: 1.5rem;
    }

    .partner-panel p {
      margin: 12px 0 20px;
      font-size: .9rem;
    }

    .partner-stat {
      display: flex;
      align-items: center;
      gap: 14px;
      padding: 15px 0;
      border-top: 1px solid rgba(255,255,255,.1);
    }

    .partner-stat-icon {
      font-size: 1.5rem;
    }

    .partner-stat strong {
      display: block;
      font-size: .92rem;
    }

    .partner-stat small {
      color: #afc1b5;
      font-size: .79rem;
    }

    /* ABOUT */

    .about-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      align-items: center;
      gap: 50px;
    }

    .about-visual {
      min-height: 320px;
      display: grid;
      place-items: center;
      border-radius: 28px;
      padding: 35px;
      background:
        radial-gradient(circle at 50% 40%, rgba(184,243,107,.17), transparent 52%),
        #e8eee2;
      border: 1px solid #dce5d7;
      text-align: center;
    }

    .about-visual .large-icon {
      font-size: 5.5rem;
    }

    .about-visual strong {
      display: block;
      font-size: 1.3rem;
      margin-top: 10px;
    }

    .about-visual p {
      color: #68776c;
      font-size: .88rem;
      margin-top: 5px;
    }

    .about-copy > p {
      color: #6b786f;
      margin-top: 17px;
    }

    .about-points {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 15px;
      margin-top: 24px;
    }

    .about-point {
      background: white;
      border: 1px solid var(--border);
      border-radius: 15px;
      padding: 16px;
    }

    .about-point strong {
      display: block;
      font-size: .9rem;
    }

    .about-point small {
      display: block;
      margin-top: 4px;
      color: #7b867e;
      font-size: .78rem;
    }

    /* BOOKING FORM */

    .booking-section {
      background: #eef2e9;
    }

    .booking-grid {
      display: grid;
      grid-template-columns: .8fr 1.2fr;
      align-items: start;
      gap: 35px;
    }

    .booking-copy {
      padding-top: 12px;
    }

    .booking-copy p {
      color: #6e7b72;
      margin-top: 15px;
    }

    .booking-contact {
      margin-top: 23px;
      padding: 18px;
      background: white;
      border: 1px solid var(--border);
      border-radius: 17px;
    }

    .booking-contact small {
      display: block;
      color: #78847b;
      font-size: .76rem;
    }

    .booking-contact strong {
      display: block;
      margin: 4px 0 10px;
      overflow-wrap: anywhere;
    }

    .booking-form {
      padding: 29px;
      background: white;
      border: 1px solid #e0e7dd;
      border-radius: 24px;
      box-shadow: var(--shadow);
    }

    .booking-form h3 {
      margin-bottom: 7px;
    }

    .form-intro {
      color: #78847b;
      font-size: .84rem;
      margin-bottom: 23px;
    }

    .form-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 16px;
    }

    .form-field {
      min-width: 0;
    }

    .form-field.full {
      grid-column: 1 / -1;
    }

    .form-field label {
      display: block;
      font-size: .81rem;
      font-weight: 800;
      margin-bottom: 7px;
    }

    .form-field input,
    .form-field select,
    .form-field textarea {
      width: 100%;
      min-width: 0;
      padding: 12px 13px;
      border: 1px solid #dce4da;
      border-radius: 11px;
      outline: none;
      background: #fcfdfb;
      color: var(--text);
    }

    .form-field input:focus,
    .form-field select:focus,
    .form-field textarea:focus {
      border-color: #83bd50;
      box-shadow: 0 0 0 3px rgba(139,217,67,.12);
    }

    .form-field textarea {
      min-height: 95px;
      resize: vertical;
    }

    .booking-form .btn {
      width: 100%;
      margin-top: 19px;
    }

    .privacy-note {
      margin-top: 12px;
      font-size: .73rem;
      color: #79857c;
      text-align: center;
    }

    /* FAQ */

    .faq-section {
      background: white;
    }

    .faq-list {
      max-width: 800px;
      display: grid;
      gap: 12px;
    }

    .faq-list details {
      border: 1px solid var(--border);
      border-radius: 15px;
      padding: 18px 20px;
      background: #fff;
    }

    .faq-list summary {
      cursor: pointer;
      font-weight: 800;
      list-style: none;
      display: flex;
      justify-content: space-between;
      gap: 15px;
    }

    .faq-list summary::after {
      content: "+";
      color: #548c26;
      font-size: 1.2rem;
    }

    .faq-list details[open] summary::after {
      content: "−";
    }

    .faq-list details p {
      padding-top: 12px;
      color: #6e7b72;
      font-size: .9rem;
    }

    /* CTA */

    .final-cta {
      padding: 55px 0;
      background: var(--green);
    }

    .cta-inner {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 25px;
    }

    .cta-inner h2 {
      font-size: clamp(1.7rem, 4vw, 2.6rem);
      color: var(--dark);
    }

    .cta-inner p {
      margin-top: 8px;
      color: #294322;
    }

    /* FOOTER */

    footer {
      padding: 55px 0 20px;
      background: #061511;
      color: white;
    }

    .footer-grid {
      display: grid;
      grid-template-columns: 1.4fr 1fr 1fr;
      gap: 35px;
      padding-bottom: 35px;
    }

    .footer-about p {
      color: #a9b8af;
      max-width: 330px;
      margin-top: 16px;
      font-size: .87rem;
    }

    .footer-column h3 {
      font-size: .98rem;
      margin-bottom: 15px;
      letter-spacing: 0;
    }

    .footer-column a,
    .footer-column p {
      display: block;
      margin: 9px 0;
      color: #b5c3ba;
      font-size: .85rem;
      overflow-wrap: anywhere;
    }

    .footer-column a:hover {
      color: var(--green);
    }

    .footer-bottom {
      padding-top: 20px;
      border-top: 1px solid rgba(255,255,255,.12);
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      gap: 10px;
      color: #91a197;
      font-size: .76rem;
    }

    .whatsapp-float {
      position: fixed;
      z-index: 150;
      bottom: 20px;
      right: 20px;
      width: 58px;
      height: 58px;
      display: grid;
      place-items: center;
      background: #25d366;
      color: white;
      border-radius: 50%;
      font-size: 1.65rem;
      box-shadow: 0 7px 25px rgba(0,0,0,.22);
      transition: transform .2s;
    }

    .whatsapp-float:hover {
      transform: scale(1.08);
    }

    /* RESPONSIVE */

    @media (max-width: 950px) {
      .nav-links {
        gap: 15px;
      }

      .nav-links a {
        font-size: .82rem;
      }

      .nav-cta {
        display: none;
      }

      .hero-grid {
        gap: 25px;
      }

      .hero-photo,
      .hero-photo img {
        min-height: 300px;
        height: 300px;
      }

      .fleet-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
      }

      .services-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
      }

      .partner-grid,
      .about-grid {
        gap: 30px;
      }
    }

    @media (max-width: 700px) {
      .section {
        padding: 62px 0;
      }

      .nav-inner {
        min-height: 68px;
      }

      .menu-toggle {
        display: block;
      }

      .nav-links {
        position: absolute;
        display: none;
        top: 68px;
        left: 0;
        right: 0;
        padding: 18px 5% 24px;
        background: #071a17;
        border-top: 1px solid rgba(255,255,255,.1);
        flex-direction: column;
        align-items: stretch;
        gap: 0;
      }

      .nav-links.open {
        display: flex;
      }

      .nav-links a {
        padding: 12px 0;
        font-size: .96rem;
      }

      .hero {
        padding: 55px 0 45px;
      }

      .hero-grid,
      .partner-grid,
      .about-grid,
      .booking-grid {
        grid-template-columns: 1fr;
      }

      .hero-copy h1 {
        font-size: clamp(2.7rem, 12vw, 4.2rem);
      }

      .hero-photo,
      .hero-photo img {
        min-height: 250px;
        height: 250px;
      }

      .trust-row {
        gap: 12px 18px;
      }

      .quick-grid {
        grid-template-columns: 1fr;
      }

      .quick-item {
        justify-content: flex-start;
        padding: 16px 4%;
        border-right: 0;
        border-bottom: 1px solid var(--border);
      }

      .quick-item:last-child {
        border-bottom: 0;
      }

      .fleet-top {
        align-items: flex-start;
        flex-direction: column;
      }

      .fleet-grid {
        grid-template-columns: 1fr;
        gap: 19px;
      }

      .car-image {
        height: 245px;
      }

      .services-grid {
        grid-template-columns: 1fr 1fr;
        gap: 12px;
      }

      .service-card {
        padding: 20px 15px;
      }

      .steps-grid {
        grid-template-columns: 1fr;
        gap: 14px;
      }

      .partner-panel {
        padding: 23px;
      }

      .about-visual {
        min-height: 250px;
      }

      .about-points {
        gap: 10px;
      }

      .booking-form {
        padding: 22px 17px;
      }

      .form-grid {
        grid-template-columns: 1fr;
      }

      .form-field.full {
        grid-column: auto;
      }

      .cta-inner {
        align-items: flex-start;
        flex-direction: column;
      }

      .footer-grid {
        grid-template-columns: 1fr 1fr;
        gap: 28px 20px;
      }

      .footer-about {
        grid-column: 1 / -1;
      }

      .footer-bottom {
        flex-direction: column;
      }

      .whatsapp-float {
        width: 53px;
        height: 53px;
        right: 15px;
        bottom: 15px;
      }
    }

    @media (max-width: 380px) {
      .brand {
        font-size: 1.08rem;
      }

      .services-grid {
        grid-template-columns: 1fr;
      }

      .car-bottom {
        align-items: flex-start;
      }

      .car-bottom .btn {
        padding: 9px 11px;
      }
    }

    @media (prefers-reduced-motion: reduce) {
      html {
        scroll-behavior: auto;
      }

      *, *::before, *::after {
        transition-duration: .01ms !important;
      }
    }
  </style>
</head>

<body>

  <!-- NAVIGATION -->
  <header class="navbar">
    <div class="container nav-inner">
      <a class="brand" href="#home" aria-label="EV Go Nepal homepage">
        <span class="brand-icon">⚡</span>
        <span>EV GO <small>NEPAL</small></span>
      </a>

      <button class="menu-toggle" id="menuToggle"
        aria-label="Open navigation menu" aria-expanded="false">
        ☰
      </button>

      <nav class="nav-links" id="navLinks">
        <a href="#home">Home</a>
        <a href="#fleet">Our Cars</a>
        <a href="#services">Services</a>
        <a href="#about">About Us</a>
        <a href="#partners">Partner With Us</a>
        <a href="#booking">Contact</a>
      </nav>

      <a class="btn btn-green nav-cta" href="#booking">Book a Car ↗</a>
    </div>
  </header>

  <main>

    <!-- HERO -->
    <section class="hero" id="home">
      <div class="container hero-grid">
        <div class="hero-copy">
          <div class="eyebrow">A smarter way to travel Nepal</div>

          <h1>Go electric.<br>Go <span>further.</span></h1>

          <p>
            Discover a better way to travel with electric car rentals.
            Find a vehicle for city rides, airport transfers, business
            journeys and trips around Nepal.
          </p>

          <div class="hero-actions">
            <a class="btn btn-green" href="#fleet">Explore Our Cars ↗</a>
            <a class="btn btn-outline" href="#partners">List Your EV</a>
          </div>

          <div class="trust-row">
            <span>Convenient booking</span>
            <span>EV-focused service</span>
            <span>Personal support</span>
          </div>
        </div>

        <div class="hero-visual">
          <div class="hero-photo">
            <img
              src="images/hero-ev.jpg"
              alt="Electric vehicle available through EV Go Nepal"
              onerror="this.style.display='none';this.nextElementSibling.hidden=false;"
            >

            <div class="hero-fallback" hidden>
              <div class="car-symbol">🚙</div>
              <strong>Your next electric journey starts here.</strong>
              <p>Add your chosen car photo as images/hero-ev.jpg</p>
            </div>

            <div class="hero-tag">
              <strong>Drive the electric future</strong>
              <span>Explore EV options in Nepal</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- QUICK BENEFITS -->
    <section class="quick-strip" aria-label="Our service benefits">
      <div class="container quick-grid">
        <div class="quick-item">
          <div class="quick-icon">🚘</div>
          <div>
            <strong>Vehicle Options</strong>
            <small>Explore different EV models</small>
          </div>
        </div>

        <div class="quick-item">
          <div class="quick-icon">📍</div>
          <div>
            <strong>Travel Your Way</strong>
            <small>Ask about your preferred route</small>
          </div>
        </div>

        <div class="quick-item">
          <div class="quick-icon">💬</div>
          <div>
            <strong>Direct Enquiries</strong>
            <small>Connect with us on WhatsApp</small>
          </div>
        </div>
      </div>
    </section>

    <!-- FLEET -->
    <section class="section fleet-section" id="fleet">
      <div class="container">
        <div class="fleet-top">
          <div class="section-heading">
            <div class="eyebrow">Explore the fleet</div>
            <h2>Find your perfect electric ride.</h2>
            <p>
              Explore popular electric vehicle models and ask us about
              availability, rental options and pricing for your journey.
            </p>
          </div>

          <a class="btn btn-dark" href="#booking">Request a Quote ↗</a>
        </div>

        <div class="fleet-grid">

          <!-- CAR 1 -->
          <article class="car-card">
            <div class="car-image">
              <span class="car-label">CITY & TRAVEL</span>
              <img src="images/byd-atto-2.jpg"
                alt="BYD Atto 2 electric SUV"
                loading="lazy"
                onerror="this.style.display='none';this.nextElementSibling.hidden=false;">
              <div class="car-placeholder" hidden>
                <div class="car-symbol">🚙</div>
                <strong>BYD Atto 2</strong>
                <p>Add photo: images/byd-atto-2.jpg</p>
              </div>
            </div>
            <div class="car-content">
              <h3>BYD Atto 2</h3>
              <p class="car-type">Compact electric SUV</p>
              <div class="car-specs">
                <span>⚡ Electric</span>
                <span>🚘 SUV</span>
                <span>🧳 Everyday travel</span>
              </div>
              <div class="car-bottom">
                <div>
                  <span class="price-label">Rental rate</span>
                  <span class="price-value">Ask for price</span>
                </div>
                <a class="btn btn-dark car-book" data-car="BYD Atto 2"
                  href="#booking">Enquire ↗</a>
              </div>
            </div>
          </article>

          <!-- CAR 2 -->
          <article class="car-card">
            <div class="car-image">
              <span class="car-label">POPULAR SUV</span>
              <img src="images/tata-nexon-ev.jpg"
                alt="Tata Nexon EV electric SUV"
                loading="lazy"
                onerror="this.style.display='none';this.nextElementSibling.hidden=false;">
              <div class="car-placeholder" hidden>
                <div class="car-symbol">🚙</div>
                <strong>Tata Nexon EV</strong>
                <p>Add photo: images/tata-nexon-ev.jpg</p>
              </div>
            </div>
            <div class="car-content">
              <h3>Tata Nexon EV</h3>
              <p class="car-type">Electric SUV</p>
              <div class="car-specs">
                <span>⚡ Electric</span>
                <span>🚘 SUV</span>
                <span>🗺️ Road trips</span>
              </div>
              <div class="car-bottom">
                <div>
                  <span class="price-label">Rental rate</span>
                  <span class="price-value">Ask for price</span>
                </div>
                <a class="btn btn-dark car-book" data-car="Tata Nexon EV"
                  href="#booking">Enquire ↗</a>
              </div>
            </div>
          </article>

          <!-- CAR 3 -->
          <article class="car-card">
            <div class="car-image">
              <span class="car-label">COMPACT EV</span>
              <img src="images/byd-dolphin.jpg"
                alt="BYD Dolphin electric hatchback"
                loading="lazy"
                onerror="this.style.display='none';this.nextElementSibling.hidden=false;">
              <div class="car-placeholder" hidden>
                <div class="car-symbol">🚗</div>
                <strong>BYD Dolphin</strong>
                <p>Add photo: images/byd-dolphin.jpg</p>
              </div>
            </div>
            <div class="car-content">
              <h3>BYD Dolphin</h3>
              <p class="car-type">Electric hatchback</p>
              <div class="car-specs">
                <span>⚡ Electric</span>
                <span>🚗 Hatchback</span>
                <span>🏙️ City journeys</span>
              </div>
              <div class="car-bottom">
                <div>
                  <span class="price-label">Rental rate</span>
                  <span class="price-value">Ask for price</span>
                </div>
                <a class="btn btn-dark car-book" data-car="BYD Dolphin"
                  href="#booking">Enquire ↗</a>
              </div>
            </div>
          </article>

          <!-- CAR 4 -->
          <article class="car-card">
            <div class="car-image">
              <span class="car-label">FAMILY SUV</span>
              <img src="images/mg-zs-ev.jpg"
                alt="MG ZS EV electric SUV"
                loading="lazy"
                onerror="this.style.display='none';this.nextElementSibling.hidden=false;">
              <div class="car-placeholder" hidden>
                <div class="car-symbol">🚙</div>
                <strong>MG ZS EV</strong>
                <p>Add photo: images/mg-zs-ev.jpg</p>
              </div>
            </div>
            <div class="car-content">
              <h3>MG ZS EV</h3>
              <p class="car-type">Electric SUV</p>
              <div class="car-specs">
                <span>⚡ Electric</span>
                <span>🚘 SUV</span>
                <span>👨‍👩‍👧 Family travel</span>
              </div>
              <div class="car-bottom">
                <div>
                  <span class="price-label">Rental rate</span>
                  <span class="price-value">Ask for price</span>
                </div>
                <a class="btn btn-dark car-book" data-car="MG ZS EV"
                  href="#booking">Enquire ↗</a>
              </div>
            </div>
          </article>

          <!-- CAR 5 -->
          <article class="car-card">
            <div class="car-image">
              <span class="car-label">CITY DRIVE</span>
              <img src="images/tata-tiago-ev.jpg"
                alt="Tata Tiago EV electric hatchback"
                loading="lazy"
                onerror="this.style.display='none';this.nextElementSibling.hidden=false;">
              <div class="car-placeholder" hidden>
                <div class="car-symbol">🚗</div>
                <strong>Tata Tiago EV</strong>
                <p>Add photo: images/tata-tiago-ev.jpg</p>
              </div>
            </div>
            <div class="car-content">
              <h3>Tata Tiago EV</h3>
              <p class="car-type">Compact electric hatchback</p>
              <div class="car-specs">
                <span>⚡ Electric</span>
                <span>🚗 Compact</span>
                <span>🏙️ City travel</span>
              </div>
              <div class="car-bottom">
                <div>
                  <span class="price-label">Rental rate</span>
                  <span class="price-value">Ask for price</span>
                </div>
                <a class="btn btn-dark car-book" data-car="Tata Tiago EV"
                  href="#booking">Enquire ↗</a>
              </div>
            </div>
          </article>

          <!-- CAR 6 -->
          <article class="car-card">
            <div class="car-image">
              <span class="car-label">ELECTRIC SUV</span>
              <img src="images/byd-atto-3.jpg"
                alt="BYD Atto 3 electric SUV"
                loading="lazy"
                onerror="this.style.display='none';this.nextElementSibling.hidden=false;">
              <div class="car-placeholder" hidden>
                <div class="car-symbol">🚙</div>
                <strong>BYD Atto 3</strong>
                <p>Add photo: images/byd-atto-3.jpg</p>
              </div>
            </div>
            <div class="car-content">
              <h3>BYD Atto 3</h3>
              <p class="car-type">Electric SUV</p>
              <div class="car-specs">
                <span>⚡ Electric</span>
                <span>🚘 SUV</span>
                <span>🛣️ Longer journeys</span>
              </div>
              <div class="car-bottom">
                <div>
                  <span class="price-label">Rental rate</span>
                  <span class="price-value">Ask for price</span>
                </div>
                <a class="btn btn-dark car-book" data-car="BYD Atto 3"
                  href="#booking">Enquire ↗</a>
              </div>
            </div>
          </article>

        </div>

        <p class="fleet-note">
          Vehicle availability, exact variants, seating, rental prices and
          driver options must be confirmed before booking. Model listings
          are examples and do not guarantee current availability.
        </p>
      </div>
    </section>

    <!-- SERVICES -->
    <section class="section services-section" id="services">
      <div class="container">
        <div class="section-heading">
          <div class="eyebrow">What we help with</div>
          <h2>One platform. More ways to travel.</h2>
          <p>
            Tell us what you need, and we will help you enquire about
            suitable electric vehicle rental options.
          </p>
        </div>

        <div class="services-grid">
          <article class="service-card">
            <div class="service-icon">🏙️</div>
            <h3>City Rides</h3>
            <p>Ask about EV options for meetings, errands and city travel.</p>
          </article>

          <article class="service-card">
            <div class="service-icon">✈️</div>
            <h3>Airport Transfers</h3>
            <p>Enquire about airport pickup and drop-off arrangements.</p>
          </article>

          <article class="service-card">
            <div class="service-icon">🏔️</div>
            <h3>Private Trips</h3>
            <p>Discuss vehicle options for your planned trip around Nepal.</p>
          </article>

          <article class="service-card">
            <div class="service-icon">💼</div>
            <h3>Business Travel</h3>
            <p>Ask about EV rental arrangements for work and business trips.</p>
          </article>
        </div>
      </div>
    </section>

    <!-- HOW IT WORKS -->
    <section class="section steps-section">
      <div class="container">
        <div class="section-heading">
          <div class="eyebrow">Simple booking process</div>
          <h2>Your journey in three steps.</h2>
          <p>
            Start an enquiry from your phone without needing to create
            an account.
          </p>
        </div>

        <div class="steps-grid">
          <article class="step-card">
            <div class="step-number">01</div>
            <h3>Choose a vehicle</h3>
            <p>Browse the EV models and decide which one suits your trip.</p>
          </article>

          <article class="step-card">
            <div class="step-number">02</div>
            <h3>Send your details</h3>
            <p>Tell us your travel date, destination and rental preferences.</p>
          </article>

          <article class="step-card">
            <div class="step-number">03</div>
            <h3>Confirm your booking</h3>
            <p>Discuss availability, final pricing and rental conditions with us.</p>
          </article>
        </div>
      </div>
    </section>

    <!-- PARTNER WITH US -->
    <section class="section partner-section" id="partners">
      <div class="container partner-grid">
        <div>
          <div class="eyebrow">For electric vehicle owners</div>
          <h2>Own an EV?<br>Let's work together.</h2>

          <p>
            EV Go Nepal aims to connect people looking for electric
            vehicle rentals with EV owners interested in potential
            rental partnerships.
          </p>

          <ul class="partner-list">
            <li>Enquire about listing your vehicle</li>
            <li>Discuss potential customer referrals</li>
            <li>Agree on rental rates and terms directly</li>
            <li>Explore opportunities for repeat bookings</li>
          </ul>

          <a class="btn btn-green" href="#booking" id="partnerButton">
            Become a Partner ↗
          </a>
        </div>

        <div class="partner-panel">
          <h3>Bring your EV into the network.</h3>
          <p>
            Tell us about your car and the type of bookings you are
            interested in. We can discuss whether a partnership is suitable.
          </p>

          <div class="partner-stat">
            <div class="partner-stat-icon">🚘</div>
            <div>
              <strong>Privately owned EVs</strong>
              <small>Ask about potential vehicle listings</small>
            </div>
          </div>

          <div class="partner-stat">
            <div class="partner-stat-icon">🤝</div>
            <div>
              <strong>Flexible arrangements</strong>
              <small>Discuss your own requirements and terms</small>
            </div>
          </div>

          <div class="partner-stat">
            <div class="partner-stat-icon">📲</div>
            <div>
              <strong>Direct communication</strong>
              <small>Start with a simple WhatsApp enquiry</small>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ABOUT -->
    <section class="section" id="about">
      <div class="container about-grid">
        <div class="about-visual">
          <div>
            <div class="large-icon">⚡🚗</div>
            <strong>Move towards electric travel.</strong>
            <p>Connecting travellers with EV rental possibilities.</p>
          </div>
        </div>

        <div class="about-copy">
          <div class="eyebrow">About EV Go Nepal</div>
          <h2>Making EV rentals easier to explore.</h2>

          <p>
            EV Go Nepal is being developed as an online platform where
            customers can explore electric car rental options and contact
            us about their travel needs.
          </p>

          <p>
            Our goal is to help customers and EV owners start a conversation
            about vehicle availability, travel requirements and possible
            rental arrangements.
          </p>

          <div class="about-points">
            <div class="about-point">
              <strong>Customer focused</strong>
              <small>Enquiries based on your trip</small>
            </div>

            <div class="about-point">
              <strong>EV focused</strong>
              <small>Electric vehicle options</small>
            </div>

            <div class="about-point">
              <strong>Clear communication</strong>
              <small>Discuss costs before confirming</small>
            </div>

            <div class="about-point">
              <strong>Partner opportunities</strong>
              <small>Connect with interested EV owners</small>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- BOOKING FORM -->
    <section class="section booking-section" id="booking">
      <div class="container booking-grid">
        <div class="booking-copy">
          <div class="eyebrow">Let's plan your trip</div>
          <h2>Where would you like to go?</h2>

          <p>
            Fill in the details and tap the button to prepare a booking
            enquiry in WhatsApp. Your booking is not confirmed until
            availability and the final terms are agreed.
          </p>

          <div class="booking-contact">
            <small>WhatsApp / Phone</small>
            <strong>9761118740</strong>
            <a class="btn btn-green" href="https://wa.me/9779761118740"
              target="_blank" rel="noopener">
              Chat on WhatsApp ↗
            </a>

            <small style="margin-top:17px;">Email</small>
            <strong>evgonep@gmail.com</strong>
            <a href="mailto:evgonep@gmail.com">Send an email ↗</a>
          </div>
        </div>

        <form class="booking-form" id="bookingForm">
          <h3>Request a rental quote</h3>
          <p class="form-intro">
            Share your details to prepare your WhatsApp enquiry.
          </p>

          <div class="form-grid">
            <div class="form-field">
              <label for="customerName">Your name *</label>
              <input id="customerName" name="customerName"
                type="text" placeholder="Enter your name" required>
            </div>

            <div class="form-field">
              <label for="customerPhone">Your phone number *</label>
              <input id="customerPhone" name="customerPhone"
                type="tel" placeholder="Your contact number" required>
            </div>

            <div class="form-field">
              <label for="carSelect">Preferred vehicle *</label>
              <select id="carSelect" name="carSelect" required>
                <option value="">Choose a vehicle</option>
                <option>BYD Atto 2</option>
                <option>Tata Nexon EV</option>
                <option>BYD Dolphin</option>
                <option>MG ZS EV</option>
                <option>Tata Tiago EV</option>
                <option>BYD Atto 3</option>
                <option>Any available EV</option>
              </select>
            </div>

            <div class="form-field">
              <label for="travelType">Rental type *</label>
              <select id="travelType" name="travelType" required>
                <option value="">Choose rental type</option>
                <option>With driver</option>
                <option>Self-drive (subject to eligibility)</option>
                <option>Airport transfer</option>
                <option>Business travel</option>
                <option>Long-distance trip</option>
                <option>Other</option>
              </select>
            </div>

            <div class="form-field">
              <label for="travelDate">Travel date</label>
              <input id="travelDate" name="travelDate" type="date">
            </div>

            <div class="form-field">
              <label for="passengers">Number of passengers</label>
              <select id="passengers" name="passengers">
                <option>1</option>
                <option>2</option>
                <option>3</option>
                <option>4</option>
                <option>5</option>
                <option>6 or more (please discuss)</option>
              </select>
            </div>

            <div class="form-field full">
              <label for="destination">Pickup and destination</label>
              <input id="destination" name="destination" type="text"
                placeholder="e.g. Kathmandu to Pokhara">
            </div>

            <div class="form-field full">
              <label for="extraDetails">Additional requirements</label>
              <textarea id="extraDetails" name="extraDetails"
                placeholder="Duration, pickup time, luggage or other details"></textarea>
            </div>
          </div>

          <button class="btn btn-green" type="submit">
            Send Enquiry on WhatsApp ↗
          </button>

          <p class="privacy-note">
            This form opens WhatsApp with your enquiry details.
            It does not process payments or automatically confirm a booking.
          </p>
        </form>
      </div>
    </section>

    <!-- FAQ -->
    <section class="section faq-section" id="faq">
      <div class="container">
        <div class="section-heading">
          <div class="eyebrow">Frequently asked questions</div>
          <h2>Good to know before you book.</h2>
        </div>

        <div class="faq-list">
          <details>
            <summary>How do I book an electric car?</summary>
            <p>
              Choose a vehicle, complete the enquiry form and send the
              details through WhatsApp. Confirm availability, price and
              rental conditions before making payment.
            </p>
          </details>

          <details>
            <summary>Are the rental prices listed on the website?</summary>
            <p>
              Prices are currently available by enquiry. The final quote
              may depend on the vehicle, trip distance, rental duration,
              driver requirements and other agreed conditions.
            </p>
          </details>

          <details>
            <summary>Can I request a car with a driver?</summary>
            <p>
              Yes, you can enquire about a car with a driver. Driver
              availability and the total cost must be confirmed for
              your particular trip.
            </p>
          </details>

          <details>
            <summary>Can I list my privately owned electric car?</summary>
            <p>
              You can contact EV Go Nepal to discuss a possible partnership.
              Any arrangement will depend on vehicle suitability, availability,
              documentation and mutually agreed terms.
            </p>
          </details>

          <details>
            <summary>Are all the vehicles shown available right now?</summary>
            <p>
              No. The vehicles shown are example models. Please ask us
              to confirm the exact model, variant, rental dates and
              availability before booking.
            </p>
          </details>
        </div>
      </div>
    </section>

    <!-- FINAL CTA -->
    <section class="final-cta">
      <div class="container cta-inner">
        <div>
          <h2>Ready for your next journey?</h2>
          <p>Tell us where you want to go and what kind of EV you need.</p>
        </div>

        <a class="btn btn-dark" href="#booking">Start Your Enquiry ↗</a>
      </div>
    </section>

  </main>

  <!-- FOOTER -->
  <footer>
    <div class="container">
      <div class="footer-grid">
        <div class="footer-about">
          <a class="brand" href="#home">
            <span class="brand-icon">⚡</span>
            <span>EV GO <small>NEPAL</small></span>
          </a>
          <p>
            An EV rental enquiry platform designed to help travellers
            explore electric car options and connect with potential
            rental partners in Nepal.
          </p>
        </div>

        <div class="footer-column">
          <h3>Explore</h3>
          <a href="#fleet">Our Cars</a>
          <a href="#services">Our Services</a>
          <a href="#about">About Us</a>
          <a href="#faq">FAQs</a>
        </div>

        <div class="footer-column">
          <h3>Contact Us</h3>
          <a href="https://wa.me/9779761118740"
            target="_blank" rel="noopener">WhatsApp: 9761118740</a>
          <a href="mailto:evgonep@gmail.com">evgonep@gmail.com</a>
          <a href="#partners">Partner With Us</a>
          <p>Nepal</p>
        </div>
      </div>

      <div class="footer-bottom">
        <span>© <span id="currentYear"></span> EV Go Nepal. All rights reserved.</span>
        <span>Electric journeys. A smarter way to travel.</span>
      </div>
    </div>
  </footer>

  <!-- FLOATING WHATSAPP BUTTON -->
  <a class="whatsapp-float"
    href="https://wa.me/9779761118740?text=Hello%20EV%20Go%20Nepal%2C%20I%20would%20like%20to%20enquire%20about%20an%20EV%20rental."
    target="_blank" rel="noopener"
    aria-label="Contact EV Go Nepal on WhatsApp">
    ☎
  </a>

  <script>
    // Mobile navigation
    const menuToggle = document.getElementById("menuToggle");
    const navLinks = document.getElementById("navLinks");

    menuToggle.addEventListener("click", function () {
      const isOpen = navLinks.classList.toggle("open");
      menuToggle.setAttribute("aria-expanded", String(isOpen));
      menuToggle.textContent = isOpen ? "×" : "☰";
    });

    // Close mobile navigation after choosing a section
    navLinks.querySelectorAll("a").forEach(function (link) {
      link.addEventListener("click", function () {
        navLinks.classList.remove("open");
        menuToggle.setAttribute("aria-expanded", "false");
        menuToggle.textContent = "☰";
      });
    });

    // Automatically fill the selected car into the enquiry form
    document.querySelectorAll(".car-book").forEach(function (button) {
      button.addEventListener("click", function () {
        document.getElementById("carSelect").value =
          button.dataset.car;
      });
    });

    // Partner button selects a partnership enquiry
    document.getElementById("partnerButton").addEventListener("click", function () {
      document.getElementById("carSelect").value = "Any available EV";
      document.getElementById("travelType").value = "Other";
      document.getElementById("extraDetails").value =
        "I own an electric vehicle and would like to discuss a potential partnership with EV Go Nepal.";
    });

    // Set the current year
    document.getElementById("currentYear").textContent =
      new Date().getFullYear();

    // Prevent selecting a past travel date
    const travelDate = document.getElementById("travelDate");
    const today = new Date();
    const localToday = [
      today.getFullYear(),
      String(today.getMonth() + 1).padStart(2, "0"),
      String(today.getDate()).padStart(2, "0")
    ].join("-");

    travelDate.min = localToday;

    // Prepare the booking message and open WhatsApp
    document.getElementById("bookingForm").addEventListener("submit", function (event) {
      event.preventDefault();

      const name = document.getElementById("customerName").value.trim();
      const phone = document.getElementById("customerPhone").value.trim();
      const car = document.getElementById("carSelect").value;
      const type = document.getElementById("travelType").value;
      const date = document.getElementById("travelDate").value || "Not specified";
      const passengers = document.getElementById("passengers").value;
      const destination = document.getElementById("destination").value.trim() || "Not specified";
      const details = document.getElementById("extraDetails").value.trim() || "None";

      if (!name || !phone || !car || !type) {
        alert("Please complete all required fields.");
        return;
      }

      const message =
        "Hello EV Go Nepal! I would like to enquire about an EV rental.\n\n" +
        "Name: " + name + "\n" +
        "My phone: " + phone + "\n" +
        "Preferred vehicle: " + car + "\n" +
        "Rental type: " + type + "\n" +
        "Travel date: " + date + "\n" +
        "Passengers: " + passengers + "\n" +
        "Pickup / destination: " + destination + "\n" +
        "Additional requirements: " + details + "\n\n" +
        "Please let me know availability and the rental price.";

      const whatsappURL =
        "https://wa.me/9779761118740?text=" +
        encodeURIComponent(message);

      window.open(whatsappURL, "_blank", "noopener");
    });
  </script>

</body>
</html>
