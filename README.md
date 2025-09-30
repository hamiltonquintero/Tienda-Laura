<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tienda Laura
    
  </title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #fdf6f9;
      color: #333;
    }

    header {
      background: #e91e63;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .product-card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
      overflow: hidden;
      text-align: center;
      padding: 10px;
      transition: transform 0.2s;
    }

    .product-card:hover {
      transform: scale(1.03);
    }

    .product-card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-bottom: 1px solid #ddd;
    }

    footer {
      background: #e91e63;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>✨ Tienda fede ✨</h1>
    <nav>
      <a href="#productos">Productos</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section id="productos" class="container">
    <div class="product-card">
      <img src="https://via.placeholder.com/200x180" alt="Labial">
      <h3>Labial Rosa</h3>
      <p>$15.000</p>
    </div>

    <div class="product-card">
      <img src="https://via.placeholder.com/200x180" alt="Base">
      <h3>Base Líquida</h3>
      <p>$30.000</p>
    </div>

    <div class="product-card">
      <img src="https://via.placeholder.com/200x180" alt="Rímel">
      <h3>Rímel Volumen</h3>
      <p>$20.000</p>
    </div>
  </section>

  <footer id="contacto">
    <p>📞 WhatsApp: +57 3135219081 | 📧 contacto@bellezatotal.com</p>
    <p>&copy; 2025 Belleza Total</p>
  </footer>

</body>
</html>
