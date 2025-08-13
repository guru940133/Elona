<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Elona Apparels</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background-color: #0B0E1A;
      color: white;
    }
    header {
      text-align: center;
      padding: 30px 10px;
      background-color: #0B0E1A;
    }
    header img {
      max-width: 200px;
      height: auto;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 30px;
      margin-top: 15px;
    }
    nav a {
      text-decoration: none;
      color: #FFD700;
      font-weight: bold;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: white;
    }
    section {
      padding: 60px 20px;
      text-align: center;
    }
    .tagline {
      font-size: 1.3rem;
      color: #FFD700;
      margin-top: 10px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #05070F;
      font-size: 0.9rem;
      color: #ccc;
    }
    .about, .collections, .contact {
      background-color: #111529;
      border-radius: 10px;
      padding: 30px;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      color: #FFD700;
    }
    button {
      background-color: #FFD700;
      border: none;
      padding: 10px 20px;
      font-size: 1rem;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    button:hover {
      background-color: #e6c200;
    }
  </style>
</head>
<body>

<header>
  <img src="1000122091.jpg" alt="Elona Apparels Logo">
  <div class="tagline">Elegance in Every Thread</div>
  <nav>
    <a href="#about">About</a>
    <a href="#collections">Collections</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="about" class="about">
  <h2>About Us</h2>
  <p>Elona Apparels is a modern luxury minimalism brand offering timeless designs crafted from the finest fabrics. Our creations embody elegance, comfort, and enduring style — for both men and women.</p>
</section>

<section id="collections" class="collections">
  <h2>Our Collections</h2>
  <p>Explore our exclusive seasonal collections blending classic silhouettes with contemporary design. From tailored menswear to sophisticated womenswear, each piece is a statement of luxury.</p>
  <button>View Lookbook</button>
</section>

<section id="contact" class="contact">
  <h2>Contact Us</h2>
  <p>Email: contact@elonaapparels.com</p>
  <p>Phone: +91 72004 78580</p>
  <p>Follow us on Instagram: @elonaapparels</p>
</section>

<footer>
  &copy; 2025 Elona Apparels. All Rights Reserved.
</footer>

</body>
</html>

