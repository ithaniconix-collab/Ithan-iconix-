<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ithan Iconix — Official Website</title>
  <style>
    body { margin:0; font-family:Arial; background:#0a0a0a; color:white; }
    header { background:#111; padding:20px; position:sticky; top:0; z-index:10; }
    nav { display:flex; justify-content:space-between; align-items:center; }
    nav a { color:white; text-decoration:none; margin:0 10px; }
    nav a:hover { color:#ff5ed0; }

    .hero { padding:60px 20px; background:linear-gradient(135deg, #ff3fd6, #ffb03a, #45f7ff); }
    .hero-grid { display:flex; flex-wrap:wrap; gap:40px; align-items:center; max-width:1100px; margin:auto; }
    .hero h1 { font-size:45px; line-height:1.1; margin:0 0 20px; }
    .hero-actions .btn { background:white; padding:10px 18px; border-radius:6px; margin-right:10px; text-decoration:none; color:black; }
    .hero-actions .btn:hover { opacity:0.8; }

    .hero-card { width:350px; background:#111; border-radius:14px; overflow:hidden; box-shadow:0 0 20px rgba(0,0,0,.4); }
    .cover { height:220px; background-size:cover; background-position:center; }
    .mini-meta { display:flex; padding:15px; gap:15px; }
    .mini-meta img { width:70px; height:70px; border-radius:8px; object-fit:cover; }
    .section { padding:80px 20px; max-width:1100px; margin:auto; }
    .section h2 { font-size:36px; margin-bottom:20px; color:#ff5ed0; }

    .gallery-grid { display:grid; grid-template-columns:repeat(auto-fit, minmax(200px,1fr)); gap:20px; }
    .gallery-grid img { width:100%; border-radius:10px; object-fit:cover; }

    footer { text-align:center; padding:30px 20px; background:#111; color:#bbb; }
  </style>
</head>

<body>

<header>
  <nav>
    <div style="font-size:22px; font-weight:bold;">ITHAN ICONIX</div>
    <div>
      <a href="#home">Home</a>
      <a href="#music">Music</a>
      <a href="#videos">Videos</a>
      <a href="#gallery">Gallery</a>
      <a href="#tour">Tour</a>
      <a href="#merch">Merch</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>
</header>

<section id="home" class="hero">
  <div class="hero-grid">
    <div>
      <h1>Vibrant Sound. Bold Energy.<br> Welcome to <span style="color:#1600ff;">Ithan Iconix</span></h1>

      <p style="max-width:400px;color:#222;font-weight:bold;">
        A colorful fusion of rhythm, melody and performance.  
        Experience the music, videos, lifestyle & more.
      </p>

      <div class="hero-actions">
        <a class="btn" href="#music">▶ Listen</a>
        <a class="btn" href="#videos">🎬 Watch</a>
        <a class="btn" href="#contact">📩 Book</a>
      </div>

      <p style="margin-top:20px;">
        Follow:
        <a href="https://www.facebook.com/m.ithan.iconix" target="_blank" style="color:#00d0ff;">Facebook</a> •
        <a href="https://youtube.com/@im_ithaniconixofficial" target="_blank" style="color:#ff006a;">YouTube</a>
      </p>
    </div>

    <div class="hero-card">
      <!-- DEMO HERO IMAGE -->
      <div class="cover" style="background-image:url('https://images.unsplash.com/photo-1511379938547-c1f69419868d?auto=format&fit=crop&w=1200&q=60');"></div>

      <div class="mini-meta">
        <!-- DEMO THUMBNAIL IMAGE -->
        <img src="https://images.unsplash.com/photo-1550831107-1553da8c8464?auto=format&fit=crop&w=400&q=60">

        <div>
          <div style="font-weight:bold;">New Single — “Light It Up”</div>
          <div style="color:#aaa;">Released 2025 • 3:21</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- MUSIC -->
<section id="music" class="section">
  <h2>MUSIC</h2>
  <p>Songs, EPs & Albums coming soon...</p>
</section>

<!-- VIDEOS -->
<section id="videos" class="section">
  <h2>VIDEOS</h2>
  <p>Official music videos will be added here.</p>
</section>

<!-- GALLERY -->
<section id="gallery" class="section">
  <h2>GALLERY</h2>
  <div class="gallery-grid">
    <img src="https://images.unsplash.com/photo-1598387993441-a364f854c3e7?auto=format&fit=crop&w=900&q=60">
    <img src="https://images.unsplash.com/photo-1553547270-499676c63edb?auto=format&fit=crop&w=900&q=60">
    <img src="https://images.unsplash.com/photo-1542208971-5fc507ccd1ee?auto=format&fit=crop&w=900&q=60">
  </div>
</section>

<!-- TOUR -->
<section id="tour" class="section">
  <h2>TOUR DATES</h2>
  <p>No tour dates yet — check back soon.</p>
</section>

<!-- MERCH -->
<section id="merch" class="section">
  <h2>MERCH</h2>
  <p>Merch store launching soon.</p>
</section>

<!-- CONTACT -->
<section id="contact" class="section">
  <h2>CONTACT / BOOKING</h2>
  <p>For bookings, collaborations, and business:</p>

  <p>Email: <b>yourbooking@email.com</b></p>
  <p>Facebook: <a href="https://www.facebook.com/m.ithan.iconix" target="_blank">Click Here</a></p>
  <p>YouTube: <a href="https://youtube.com/@im_ithaniconixofficial" target="_blank">Click Here</a></p>
</section>

<footer>
  © 2025 Ithan Iconix. All rights reserved.
</footer>

</body>
</html>
