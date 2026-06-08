<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>IronFit Gym | Start Your Transformation</title>
  <meta name="description" content="IronFit Gym - Modern fitness center offering personal training, group classes, nutrition coaching, and memberships. Book your free trial today!">
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background: #111;
      color: #fff;
    }
    header {
      background: #000;
      padding: 1rem;
    }
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .nav-links {
      list-style: none;
      display: flex;
      gap: 1rem;
    }
    .nav-links a {
      color: #fff;
      text-decoration: none;
    }
    .btn-primary {
      background: #00aaff;
      color: #fff;
      padding: 0.5rem 1rem;
      text-decoration: none;
      border-radius: 4px;
    }
    .btn-secondary {
      background: #444;
      color: #fff;
      padding: 0.5rem 1rem;
      border-radius: 4px;
    }
    .hero {
      text-align: center;
      padding: 5rem 2rem;
      background: url('images/hero.jpg') center/cover no-repeat;
    }
    .section {
      padding: 3rem 2rem;
    }
    .pricing {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
    }
    .card {
      background: #222;
      padding: 1rem;
      border-radius: 8px;
      text-align: center;
      flex: 1;
      min-width: 150px;
    }
    .trainer-gallery {
      display: flex;
      gap: 2rem;
      flex-wrap: wrap;
    }
    .trainer img {
      width: 150px;
      border-radius: 8px;
    }
    footer {
      background: #000;
      text-align: center;
      padding: 1rem;
    }
    input, textarea {
      display: block;
      width: 100%;
      margin: 0.5rem 0;
      padding: 0.5rem;
      border-radius: 4px;
      border: none;
    }
    button {
      padding: 0.5rem 1rem;
      border: none;
      border-radius: 4px;
      background: #00aaff;
      color: #fff;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <!-- Navigation -->
  <header>
    <nav class="navbar">
      <div class="logo">IronFit Gym</div>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#classes">Classes</a></li>
        <li><a href="#membership">Membership</a></li>
        <li><a href="#trainers">Trainers</a></li>
        <li><a href="#blog">Blog</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
      <a href="#trial" class="btn-primary">Book Free Trial</a>
    </nav>
  </header>

  <!-- Hero -->
  <section id="home" class="hero">
    <h1>Start Your Transformation Today</h1>
    <p>Your journey to strength, confidence, and health begins here.</p>
    <div class="hero-buttons">
      <a href="#trial" class="btn-primary">Book Free Trial</a>
      <a href="#membership" class="btn-secondary">Join Now</a>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="section">
    <h2>About IronFit Gym</h2>
    <p>Founded to empower busy professionals, athletes, and beginners, IronFit Gym transforms lives through fitness, nutrition, and motivation.</p>
    <div class="gallery">
      <img src="images/gym1.jpg" alt="Gym Facility" width="250">
      <img src="images/gym2.jpg" alt="Training Area" width="250">
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="section">
    <h2>Our Services</h2>
    <ul>
      <li>Personal Training</li>
      <li>Group Classes</li>
      <li>Nutrition Coaching</li>
      <li>Open Gym</li>
      <li>Kids Programs</li>
    </ul>
  </section>

  <!-- Classes -->
  <section id="classes" class="section">
    <h2>Classes</h2>
    <div id="class-schedule"></div>
  </section>

  <!-- Membership -->
  <section id="membership" class="section">
    <h2>Membership Plans</h2>
    <div class="pricing">
      <div class="card"><h3>Day Pass</h3><p>$10</p></div>
      <div class="card"><h3>Monthly</h3><p>$60</p></div>
      <div class="card"><h3>3-Month</h3><p>$150</p></div>
      <div class="card"><h3>6-Month</h3><p>$280</p></div>
      <div class="card"><h3>Yearly</h3><p>$500</p></div>
    </div>
  </section>

  <!-- Trainers -->
  <section id="trainers" class="section">
    <h2>Meet Our Trainers</h2>
    <div class="trainer-gallery">
      <div class="trainer">
        <img src="images/trainer1.jpg" alt="John Carter">
        <p><strong>John Carter</strong> – Strength & Conditioning Specialist</p>
      </div>
      <div class="trainer">
        <img src="images/trainer2.jpg" alt="Maria Lopez">
        <p><strong>Maria Lopez</strong> – Yoga & Mindfulness Coach</p>
      </div>
    </div>
  </section>

  <!-- Testimonials -->
  <section id="testimonials" class="section">
    <h2>Success Stories</h2>
    <blockquote>“IronFit changed my life. I lost 30 lbs and gained confidence!”</blockquote>
    <img src="images/before-after.jpg" alt="Member Transformation" width="300">
  </section>

  <!-- Blog -->
  <section id="blog" class="section">
    <h2>Fitness Tips & Blog</h2>
    <input type="search" id="blog-search" placeholder="Search posts...">
    <div id="blog-posts"></div>
  </section>

  <!-- Contact -->
  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <form id="contact-form">
      <input type="text" name="name" placeholder="Name" required>
      <input type="email" name="email" placeholder="Email" required>
      <input type="tel" name="phone" placeholder="Phone">
      <textarea name="message" placeholder="Message"></textarea>
      <button type="submit" class="btn-primary">Send Message</button>
    </form>
    <p>Phone: <a href="tel:+251911123456">+251-911-123456</a></p>
    <p>Email: info@ironfitgym.com</p>
    <p>Hours: Mon–Fri 6am–10pm, Sat–Sun 8am–8pm</p>
    <div id="map">[Google Maps Embed Here]</div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 IronFit Gym</p>
    <div class="social">
      <a href="#">Instagram</a> | <a href="#">Facebook</a> | <a href="#">TikTok</a>
    </div>
  </footer>

  <script>
    // Contact form handler
    document.getElementById('contact-form').addEventListener('submit', e => {
      e.preventDefault();
      alert('Thank you! We will contact you soon.');
    });

    // Example class schedule rendering
    const schedule = [
      { day: 'Monday', class: 'HIIT - 6pm' },
      { day: 'Tuesday', class: 'Yoga - 7am' },
      { day: 'Wednesday', class: 'Strength Training - 6pm' },
      { day: 'Thursday', class: 'Spinning - 7pm' },
      { day: 'Friday', class: 'Zumba - 6pm' }
    ];
    const scheduleDiv = document.getElementById('class-schedule
