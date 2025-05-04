<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Urban Gents - Men's Wear</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background-color: #f4f4f4;
    }
    header {
      background-color: #1a1a1a;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #333;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: block;
    }
    nav a:hover {
      background-color: #575757;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1521335629791-ce4aec67ddaf') center/cover no-repeat;
      color: white;
      padding: 100px 20px;
      text-align: center;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px;
    }
    .product {
      background-color: white;
      border-radius: 8px;
      padding: 20px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      max-width: 100%;
      height: auto;
      border-radius: 5px;
    }
    .product h3 {
      margin: 10px 0 5px;
    }
    .product p {
      color: #555;
    }
    .product button {
      background-color: #1a1a1a;
      color: white;
      border: none;
      padding: 10px 20px;
      margin-top: 10px;
      cursor: pointer;
      border-radius: 5px;
    }
    .product button:hover {
      background-color: #333;
    }
    footer {
      background-color: #1a1a1a;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Urban Gents</h1>
    <p>Classic & Modern Men's Wear</p>
  </header>
  <nav>
    <a href="#">Home</a>
    <a href="#">Shop</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>
  <div class="hero">
    <h2>Refine Your Style</h2>
    <p>Discover premium fashion for the modern man.</p>
  </div>
  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/250x300" alt="Slim Fit Shirt" />
      <h3>Slim Fit Shirt</h3>
      <p>$29.99</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x300" alt="Classic Jeans" />
      <h3>Classic Jeans</h3>
      <p>$39.99</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x300" alt="Bomber Jacket" />
      <h3>Bomber Jacket</h3>
      <p>$59.99</p>
      <button>Add to Cart</button>
    </div>
  </section>
  <footer>
    <p>&copy; 2025 Urban Gents. All rights reserved.</p>
  </footer>
</body>
</html>
