<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>UrbanCart - Grocery & Textile Store</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: white;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 30px;
      background: #020617;
    }
    .logo {
      font-size: 24px;
      font-weight: bold;
      color: #38bdf8;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: white;
    }
    .hero {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(to right, #0ea5e9, #6366f1);
    }
    .hero h1 {
      font-size: 40px;
    }
    .btn {
      padding: 10px 20px;
      background: #020617;
      border: none;
      color: white;
      cursor: pointer;
      margin-top: 15px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 30px;
    }
    .card {
      background: #1e293b;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
    }
    .card img {
      width: 100%;
      border-radius: 10px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #020617;
    }
  </style>
</head>
<body>

<header>
  <div class="logo">🛒 UrbanCart</div>
  <nav>
    <a href="#">Home</a>
    <a href="#">Grocery</a>
    <a href="#">Textile</a>
    <a href="#">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>Everything You Need in One Place</h1>
  <p>Groceries & Fashion at Best Prices</p>
  <button class="btn">Shop Now</button>
</section>

<section class="products">
  <div class="card">
    <img src="https://via.placeholder.com/200" alt="Rice">
    <h3>Premium Rice</h3>
    <p>₹120/kg</p>
    <button class="btn">Add to Cart</button>
  </div>

  <div class="card">
    <img src="https://via.placeholder.com/200" alt="Shirt">
    <h3>Casual Shirt</h3>
    <p>₹799</p>
    <button class="btn">Add to Cart</button>
  </div>

  <div class="card">
    <img src="https://via.placeholder.com/200" alt="Vegetables">
    <h3>Fresh Vegetables</h3>
    <p>₹50/kg</p>
    <button class="btn">Add to Cart</button>
  </div>

  <div class="card">
    <img src="https://via.placeholder.com/200" alt="Jeans">
    <h3>Denim Jeans</h3>
    <p>₹1299</p>
    <button class="btn">Add to Cart</button>
  </div>
</section>

<footer>
  <p>© 2026 UrbanCart | All Rights Reserved</p>
</footer>

</body>
</html>
