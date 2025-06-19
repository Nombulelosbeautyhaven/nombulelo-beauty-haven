<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nombulelo's Beauty Haven</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #fff5f8;
      color: #333;
    }
    header {
      background-color: #ff69b4;
      padding: 20px;
      text-align: center;
      color: white;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #ffc0cb;
      padding: 10px;
    }
    nav a {
      color: #333;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
    }
    .services, .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }
    .card {
      background: white;
      border-radius: 10px;
      padding: 20px;
      margin: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      width: 300px;
    }
    footer {
      background-color: #ff69b4;
      color: white;
      text-align: center;
      padding: 20px;
    }
    img {
      width: 100%;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Nombulelo's Beauty Haven</h1>
    <p>Mobile Salon | Call or WhatsApp: 064 790 4034</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home">
    <h2>Welcome to Nombulelo's Beauty Haven</h2>
    <p>Where beauty meets convenience. We bring professional salon services right to your doorstep.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">
        <h3>Hair Styling</h3>
        <p>We style all hair types – from braids to blowouts.</p>
      </div>
      <div class="card">
        <h3>Manicure & Pedicure</h3>
        <p>Relax and refresh with a spa-quality mani/pedi.</p>
      </div>
      <div class="card">
        <h3>Facials</h3>
        <p>Deep cleanse and glow with our skincare treatments.</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>Nombulelo's Beauty Haven is a proudly South African mobile salon founded with a passion for making people feel confident and beautiful—right from the comfort of their home.</p>
  </section>

  <section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
      <div class="card"><img src="https://via.placeholder.com/300x200" alt="Hair style" /></div>
      <div class="card"><img src="https://via.placeholder.com/300x200" alt="Nails" /></div>
      <div class="card"><img src="https://via.placeholder.com/300x200" alt="Facial" /></div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Phone:</strong> 064 790 4034</p>
    <p><strong>WhatsApp:</strong> Click to chat: <a href="https://wa.me/27647904034">wa.me/27647904034</a></p>
    <p><strong>Email:</strong> info@nombubeauty.co.za</p>
  </section>

  <footer>
    <p>&copy; 2025 Nombulelo's Beauty Haven. All rights reserved.</p>
  </footer>

</body>
</html>
