<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Nelly Digital — Vision Beyond Sound</title>
  <meta name="description" content="Nelly Digital — Graphics & web design for students, schools and startups in Kampala. Vision beyond sound." />
  <!-- Open Graph -->
  <meta property="og:title" content="Nelly Digital — Vision Beyond Sound" />
  <meta property="og:description" content="Graphics & web design for students, schools and startups in Kampala." />
  <meta property="og:image" content="assets/og-image.jpg" />
  <meta property="og:type" content="website" />
  <link rel="icon" href="assets/favicon.png" />

  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --brand-red: #8B0000;
      --brand-pink: #f5dcdc;
      --bg: #ffffff;
      --muted: #666666;
      --max-width: 1080px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: 'Poppins', system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      color:#111;
      background:var(--bg);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.45;
    }

    /* Layout */
    .container{max-width:var(--max-width);margin:0 auto;padding:0 20px;}
    header{background:linear-gradient(90deg,var(--brand-red) 0%, #7a0000 100%);color:#fff;padding:28px 0;}
    .brand{display:flex;align-items:center;gap:16px;justify-content:space-between;}
    .brand .left{display:flex;align-items:center;gap:14px;}
    .logo {display:flex;align-items:center;gap:10px;text-decoration:none;color:inherit}
    .logo .mark{width:46px;height:46px;background:#fff;border-radius:6px;display:inline-flex;align-items:center;justify-content:center;color:var(--brand-red);font-weight:700}
    .logo h1{font-size:20px;margin:0;letter-spacing:0.2px}
    nav{display:flex;gap:12px;align-items:center}
    nav a{color:rgba(255,255,255,0.95);text-decoration:none;padding:8px 10px;border-radius:6px;font-weight:600}
    nav a:hover{background:rgba(0,0,0,0.08)}

    /* Hero */
    .hero{padding:56px 0;display:grid;grid-template-columns:1fr 420px;gap:32px;align-items:center}
    .hero .eyebrow{color:rgba(255,255,255,0.95);font-weight:600;opacity:0.95}
    .hero h2{font-size:44px;color:#fff;margin:12px 0 12px;line-height:1.05}
    .hero p.lead{color:rgba(255,255,255,0.95);max-width:560px}
    .cta-group{margin-top:20px;display:flex;gap:12px}
    .btn{background:#fff;color:var(--brand-red);padding:12px 18px;border-radius:8px;text-decoration:none;font-weight:700}
    .btn.secondary{background:transparent;border:2px solid rgba(255,255,255,0.18);color:#fff}

    /* Card */
    .hero-card{background:#fff;border-radius:10px;padding:18px;box-shadow:0 10px 30px rgba(0,0,0,0.08)}
    .hero-card h3{margin:0 0 8px;font-size:20px;color:var(--brand-red)}
    .price{font-weight:700;font-size:22px;color:#111}

    /* Sections */
    section{padding:48px 0}
    h3.section-title{font-size:24px;color:var(--brand-red);margin:0 0 20px}
    .about{display:grid;grid-template-columns:1fr 360px;gap:28px;align-items:center}
    .about p{color:var(--muted)}

    /* Services */
    .services-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px}
    .service{background:#fff;padding:18px;border-radius:8px;box-shadow:0 6px 18px rgba(0,0,0,0.06)}
    .service h4{margin:0 0 6px}
    .service p{margin:0;color:var(--muted);font-size:14px}

    /* Portfolio */
    .portfolio-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:12px}
    .portfolio-item{background:#f7f7f7;border-radius:8px;overflow:hidden;min-height:140px;display:flex;align-items:center;justify-content:center}
    .portfolio-item img{width:100%;height:100%;object-fit:cover}

    /* Testimonials */
    .test{background:linear-gradient(180deg,#fff,#f9f9f9);padding:18px;border-radius:8px;margin-bottom:12px}

    /* Contact */
    .contact{background:#fafafa;border-radius:12px;padding:22px;display:grid;grid-template-columns:1fr 360px;gap:18px;align-items:center}
    .contact .phones{display:flex;flex-direction:column;gap:6px}
    .whatsapp{display:inline-flex;align-items:center;gap:8px;background: #25D366;padding:10px 14px;color:#fff;border-radius:8px;font-weight:700;text-decoration:none}

    /* Footer */
    footer{padding:28px 0;color:var(--muted);text-align:center;font-size:14px}

    /* Responsive */
    @media (max-width:880px){
      .hero{grid-template-columns:1fr; text-align:left}
      .about{grid-template-columns:1fr}
      .contact{grid-template-columns:1fr}
      nav{display:none}
    }
  </style>
</head>
<body>

  <header>
    <div class="container brand">
      <div class="left">
        <a class="logo" href="#">
          <div class="mark" aria-hidden="true">ND</div>
          <div>
            <h1>Nelly Digital</h1>
            <div style="font-size:12px;color:rgba(255,255,255,0.9)">Vision Beyond Sound</div>
          </div>
        </a>
      </div>

      <nav aria-label="Main navigation">
        <a href="#services">Services</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <!-- HERO -->
    <section class="hero" aria-label="Intro">
      <div>
        <div class="eyebrow">Graphics & Web for Students and Startups — Kampala</div>
        <h2>Designs that speak louder than sound.</h2>
        <p class="lead">I help schools, students and local businesses look professional online — logos, websites, social branding and print that convert.</p>

        <div class="cta-group" role="group">
          <a class="btn" href="#contact">Start your project</a>
          <a class="btn secondary" href="#portfolio">View work</a>
        </div>
      </div>

      <aside class="hero-card" aria-label="Quick package">
        <h3>Starter Package</h3>
        <div class="price">UGX 75,000</div>
        <p style="color:var(--muted);margin-top:8px">Logo + 1-page site</p>
        <a class="btn" href="https://wa.me/256786336335?text=Hi%20Nelly,%20I'm%20interested%20in%20the%20Starter%20Package">Book on WhatsApp</a>
      </aside>
    </section>

    <!-- ABOUT -->
    <section id="about" class="about">
      <div>
        <h3 class="section-title">About Nelly</h3>
        <p>I’m Nelly — a web & graphics designer based in Kampala. I lost part of my hearing while studying, and that sharpened how I see design. I build visual systems that help businesses and students get noticed and trusted online.</p>
        <p style="margin-top:8px;color:var(--muted)">I focus on fast delivery, clear communication, and real outcomes: more leads, better professional presence, and confident clients.</p>
      </div>
      <div>
        <!-- Optional testimonial / quick stats -->
        <div class="test"><strong>Quick wins:</strong><br> 5+ student brands launched • 10+ local businesses improved their presence</div>
        <div class="test"><strong>Work style:</strong><br> Fast turnarounds • Transparent pricing • Simple upgrades</div>
      </div>
    </section>

    <!-- SERVICES -->
    <section id="services">
      <h3 class="section-title">Services</h3>
      <div class="services-grid">
        <div class="service">
          <h4>Brand Identity</h4>
          <p>Create a clean logo, color palette, and typography system that works across print and digital.</p>
        </div>
        <div class="service">
          <h4>Web Design</h4>
          <p>Fast, mobile-first HTML/CSS websites you can host on GitHub Pages. Optimized for speed and clarity.</p>
        </div>
        <div class="service">
          <h4>Social & Print Design</h4>
          <p>Flyers, posters, Instagram templates, and WhatsApp banners for events and promotions.</p>
        </div>
        <div class="service">
          <h4>Workshops & Student Kits</h4>
          <p>Short sessions and affordable brand kits for students starting side-hustles.</p>
        </div>
      </div>
    </section>

    <!-- PORTFOLIO -->
    <section id="portfolio">
      <h3 class="section-title">Featured Work</h3>
      <div class="portfolio-grid" aria-live="polite">
        <!-- Replace placeholder images with your screenshots (see assets notes) -->
        <div class="portfolio-item"><img src="assets/portfolio1.jpg" alt="Logo and flyer example"></div>
        <div class="portfolio-item"><img src="assets/portfolio2.jpg" alt="Website mockup"></div>
        <div class="portfolio-item"><img src="assets/portfolio3.jpg" alt="Social templates"></div>
        <div class="portfolio-item"><img src="assets/portfolio4.jpg" alt="Before and after design"></div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact">
      <h3 class="section-title">Contact & Bookings</h3>
      <div class="contact" role="region" aria-label="Contact section">
        <div>
          <p style="margin:0 0 8px">Ready to start? Message me on WhatsApp or send a quick note.</p>

          <!-- WhatsApp CTA -->
          <a class="whatsapp" href="https://wa.me/256786336335?text=Hi%20Nelly,%20I%27d%20like%20to%20book%20a%20design%20service" target="_blank" rel="noopener">
            <!-- simple inline svg icon -->
            <svg width="18" height="18" viewBox="0 0 24 24" fill="#fff" style="flex:0 0 18px" aria-hidden="true">
              <path d="M20.5 3.5c-4-4-10-4-14 0-2 2-3 4-3.5 6.5L2 21l11-1.5c2.6-.4 4.7-1.9 6.5-3.5 4-4 4-10 0-14z"/>
            </svg>
            WhatsApp: 0786 336 335
          </a>

          <div style="margin-top:12px" class="phones">
            <div><strong>Email</strong>: <a href="mailto:youremail@example.com">youremail@example.com</a></div>
            <div><strong>Location</strong>: Kampala, Uganda</div>
          </div>
        </div>

        <!-- Optional contact form (Formspree example) - replace action with your form endpoint -->
        <form method="POST" action="https://formspree.io/f/YOUR_FORM_ID" style="display:flex;flex-direction:column;gap:10px">
          <input name="name" type="text" placeholder="Your name" required style="padding:10px;border-radius:6px;border:1px solid #ddd">
          <input name="email" type="email" placeholder="Your email" required style="padding:10px;border-radius:6px;border:1px solid #ddd">
          <textarea name="message" rows="4" placeholder="Briefly describe your project" style="padding:10px;border-radius:6px;border:1px solid #ddd"></textarea>
          <button type="submit" class="btn" style="align-self:flex-start">Send Message</button>
        </form>
      </div>
    </section>

  </main>

  <footer>
    <div class="container">
      © <span id="year"></span> Nelly Digital — Vision Beyond Sound · <a href="#" style="color:var(--muted);text-decoration:none">Terms</a>
    </div>
  </footer>

<script>
  // small scripts
  document.getElementById('year').textContent = new Date().getFullYear();
</script>

</body>
</html>
