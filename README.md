<!doctype html>
<html lang="hi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Hidden India Trails — Uttarakhand & Leh-Ladakh Tours</title>
  <meta name="description" content="Hidden India Trails — Explore Uttarakhand & Leh-Ladakh with local guides. Custom tours, treks & experiences.">
  <link rel="stylesheet" href="styles.css">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>
<body>
  <header class="site-header">
    <div class="brand">
      <h1>Hidden India Trails</h1>
      <
				p class="tag">Uttarakhand • Leh-Ladakh • Hidden Trails</p>
    </div>
    <nav class="nav">
      <a href="#home">Home</a>
      <a href="#destinations">Destinations</a>
      <a href="#packages">Packages</a>
      <a href="#gallery">Gallery</a>
      <a href="#booking">Booking</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main id="home">
    <section class="hero">
      <div class="hero-content">
        <h2>Discover the Hidden Trails of India</h2>
        <p>Authentic journeys through Uttarakhand’s Urgam Valley & Leh–Ladakh — adventure, spirituality, and nature.</p>
        <div class="hero-actions">
          <a class="btn primary" href="#packages">View Packages</a>
          <a class="btn ghost" href="#booking">Book Now</a>
        </div>
      </div>
    </section>

    <section id="destinations" class="section">
      <h3>Popular Destinations</h3>
      <div class="cards">
        <article class="card">
          <div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1501785888041-af3ef285b470?w=1000&q=80');"></div>
          <h4>Urgam Valley, Chamoli</h4>
          <p>Serene homestays, village life & hidden Himalayan trails.</p>
        </article>
        <article class="card">
          <div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?w=1000&q=80');"></div>
          <h4>Leh–Ladakh</h4>
          <p>Monasteries, high passes, and stunning desert mountains.</p>
        </article>
      </div>
    </section>

    <section id="gallery" class="section alt">
      <h3>Photo Gallery</h3>
      <p>Experience the beauty of the Himalayas — from local villages to snow peaks.</p>
      <div class="gallery">
        <img src="https://images.unsplash.com/photo-1500534314209-a25ddb2bd429?w=600&q=80" alt="Himalayan trail">
        <img src="https://images.unsplash.com/photo-1470770841072-f978cf4d019e?w=600&q=80" alt="Monastery">
        <img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?w=600&q=80" alt="Urgam Valley">
        <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?w=600&q=80" alt="Leh Ladakh">
        <img src="https://images.unsplash.com/photo-1499696010180-025ef6e1a1ed?w=600&q=80" alt="Trekking">
        <img src="https://images.unsplash.com/photo-1523528283115-0f3d426bff63?w=600&q=80" alt="Camping">
      </div>
    </section>

    <section id="packages" class="section">
      <h3>Packages</h3>
      <div class="package-list">
        <div class="package">
          <h4>Urgam Valley Explorer</h4>
          <p>4 Nights • Local homestay • Guided hikes</p>
          <a class="btn small" href="#booking">Book Now</a>
        </div>
        <div class="package">
          <h4>Leh–Ladakh Adventure</h4>
          <p>7 Nights • Jeep tour • Local guide</p>
          <a class="btn small" href="#booking">Book Now</a>
        </div>
      </div>
    </section>

    <section id="booking" class="section booking-section">
      <h3>Booking Form</h3>
      <p>Fill out this form and we’ll contact you within 24 hours.</p>
      <form action="https://formspree.io/f/xnnqkzlb" method="POST" class="booking-form">
        <label>Name</label>
        <input type="text" name="name" placeholder="Your full name" required>
        <label>Email</label>
        <input type="email" name="email" placeholder="Your email address" required>
        <label>Destination / Package</label>
        <input type="text" name="package" placeholder="e.g. Urgam Valley Explorer" required>
        <label>Message</label>
        <textarea name="message" rows="4" placeholder="Tell us your preferred dates or special requests"></textarea>
        <button type="submit" class="btn primary">Send Booking Request</button>
      </form>
    </section>

    <section id="contact" class="section contact-section">
      <h3>Contact</h3>
      <p>Email: <a href="mailto:narennegi7172@gmail.com">narennegi7172@gmail.com</a></p>
      <p>Location: Urgam Valley, Chamoli, Uttarakhand</p>
      <p>Instagram: <a href="https://instagram.com/hhiddenindiatrails" target="_blank">@hhiddenindiatrails</a></p>
    </section>
  </main>

  <footer class="site-footer">
    <p>© <span id="year"></span> Hidden India Trails — Uttarakhand & Leh-Ladakh</p>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
