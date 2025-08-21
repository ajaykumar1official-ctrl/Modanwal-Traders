<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Modanwal TRADERS - Submersible Sellers</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f8f9fa;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #0077b6;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }
    nav {
      background: #023e8a;
      text-align: center;
      padding: 10px 0;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      padding: 0 15px;
      font-size: 18px;
    }
    nav a:hover { text-decoration: underline; }
    .container { max-width: 900px; margin: 30px auto; padding: 0 20px; }
    .section { margin-bottom: 40px; }
    h2 { color: #023e8a; }
    .products {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: space-around;
    }
    .product-card {
      background: #fff;
      border: 1px solid #ddd;
      border-radius: 10px;
      width: 260px;
      padding: 15px;
      text-align: center;
    }
    .product-card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 10px;
    }
    form {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      border: 1px solid #ddd;
      max-width: 450px;
      margin: auto;
    }
    label { display: block; margin-top: 15px; }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border-radius: 5px;
      border: 1px solid #ccc;
      box-sizing: border-box;
    }
    button {
      background: #0077b6;
      color: #fff;
      padding: 12px 30px;
      border: none;
      border-radius: 5px;
      margin-top: 15px;
      cursor: pointer;
      font-size: 16px;
    }
    button:hover { background: #023e8a; }
    .map-container {
      margin-top: 30px;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 2px 8px rgba(0,0,0,0.2);
    }
    footer {
      text-align: center;
      padding: 15px 0;
      background: #023e8a;
      color: #fff;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Modanwal TRADERS</h1>
    <p>Your Reliable Submersible Providers</p>
  </header>
  <nav>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>
  <div class="container">
    <section id="about" class="section">
      <h2>About Modanwal TRADERS</h2>
      <p>
        Modanwal TRADERS specializes in high-quality submersibles for agricultural, domestic, and industrial applications. Trusted by our customers for our reliability and service, we offer a range of energy-efficient, long-lasting submersible pumps tailored for various needs.
      </p>
    </section>
    <section id="products" class="section">
      <h2>Our Products</h2>
      <div class="products">
        <div class="product-card">
          <img src="https://via.placeholder.com/250x150?text=Submersible+Pump+1" alt="Submersible Pump"/>
          <h3>High-Performance Submersible</h3>
          <p>Stainless steel, 1.5HP, for deep wells.</p>
          <p><b>Price:</b> ₹7,500</p>
        </div>
        <div class="product-card">
          <img src="https://via.placeholder.com/250x150?text=Submersible+Pump+2" alt="Submersible Pump"/>
          <h3>Domestic Submersible Pump</h3>
          <p>Energy-efficient, 1HP, easy installation.</p>
          <p><b>Price:</b> ₹4,800</p>
        </div>
        <div class="product-card">
          <img src="https://via.placeholder.com/250x150?text=Submersible+Pump+3" alt="Submersible Pump"/>
          <h3>Industrial Submersible</h3>
          <p>Heavy-duty, 3HP, corrosion resistant.</p>
          <p><b>Price:</b> ₹13,200</p>
        </div>
      </div>
    </section>
    <section id="contact" class="section">
      <h2>Contact Us</h2>
      <form>
        <label for="name">Name*</label>
        <input type="text" id="name" required />

        <label for="email">Email*</label>
        <input type="email" id="email" required />

        <label for="message">Message*</label>
        <textarea id="message" rows="4" required></textarea>

        <button type="submit">Send Inquiry</button>
      </form>

      <!-- Google Map Embed -->
      <div class="map-container">
        <iframe
          src="https://www.google.com/maps?q=3VHG%2BPM6+Kishori+Lal+sweet+house,+Phoolpur,+Uttar+Pradesh+276304&output=embed"
          width="100%"
          height="350"
          style="border:0;"
          allowfullscreen=""
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade">
        </iframe>
      </div>
    </section>
  </div>
  <footer>
    &copy; 2025 Modanwal TRADERS - All Rights Reserved
  </footer>
</body>
</html>
