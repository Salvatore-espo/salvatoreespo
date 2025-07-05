<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Salvatore Espo - Luxury Fashion for Men and Women">
  <title>Salvatore Espo</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Playfair Display', serif;
      background: #fff;
      color: #111;
    }
    header {
      background: #000;
      color: #fff;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
      letter-spacing: 2px;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
      background-color: #f5f5f5;
    }
    nav a {
      text-decoration: none;
      color: #111;
      font-weight: 600;
    }
    section.hero {
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 4rem;
      background-image: url('https://via.placeholder.com/1400x600');
      background-size: cover;
      background-position: center;
      color: white;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.7);
      text-align: center;
    }
    section.hero h2 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    section.hero p {
      font-size: 1.2rem;
    }
    section.products {
      padding: 3rem 2rem;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .product {
      border: 1px solid #ccc;
      padding: 1rem;
      text-align: center;
      background: #fff;
    }
    .product img {
      width: 100%;
      height: auto;
    }
    .product h3 {
      margin: 1rem 0 0.5rem;
    }
    .product p {
      color: #666;
    }
    footer {
      background: #000;
      color: #fff;
      text-align: center;
      padding: 1rem;
    }
    .vip-signup {
      background-color: #f0e6d2;
      padding: 2rem;
      text-align: center;
    }
    .vip-signup input {
      padding: 0.5rem;
      margin-top: 1rem;
      width: 200px;
    }
  </style>
</head>
<body>
  <header>
    <h1>SALVATORE ESPO</h1>
  </header>
  <nav>
    <a href="#men">Men</a>
    <a href="#women">Women</a>
    <a href="#vip">VIP Signup</a>
    <a href="#cart">Cart</a>
  </nav>
  <section class="hero">
    <div>
      <h2>Luxury Fashion, Timeless Design</h2>
      <p>Crafted for the elite. Loved by the bold.</p>
    </div>
  </section>
  <section class="products" id="men">
    <div class="product">
      <img src="https://via.placeholder.com/300x400" alt="Men's Polo">
      <h3>Men's Polo</h3>
      <p>$220 AUD</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x400" alt="Men's Jacket">
      <h3>Luxury Jacket</h3>
      <p>$540 AUD</p>
    </div>
  </section>
  <section class="products" id="women">
    <div class="product">
      <img src="https://via.placeholder.com/300x400" alt="Women's Sport Top">
      <h3>Women's Top</h3>
      <p>$180 AUD</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x400" alt="Track Set">
      <h3>Women's Track Pants</h3>
      <p>$290 AUD</p>
    </div>
  </section>
  <section class="vip-signup" id="vip">
    <h2>Join the VIP Circle</h2>
    <p>Get exclusive early access and updates.</p>
    <input type="email" placeholder="Enter your email">
  </section>
  <footer>
    <p>&copy; 2025 Salvatore Espo. All rights reserved.</p>
  </footer>
</body>
</html>
