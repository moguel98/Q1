<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Catálogo Apolo Group</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background-color: #f8f8f8;
      color: #333;
    }

    header {
      background: linear-gradient(to right, #ff914d, #ff5e62);
      padding: 30px 20px;
      color: white;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2em;
    }

    nav {
      text-align: center;
      padding: 15px;
      background: #fff;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #ff5e62;
      font-weight: bold;
    }

    .section {
      padding: 20px;
    }

    .section h2 {
      color: #ff5e62;
      border-bottom: 2px solid #ff914d;
      padding-bottom: 5px;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .product {
      background: #fff;
      padding: 15px;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: center;
    }

    .product img {
      max-width: 100%;
      border-radius: 8px;
    }

    .product h3 {
      margin: 10px 0 5px;
      font-size: 1em;
    }

    .product p {
      margin: 0;
      font-size: 0.9em;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #ff5e62;
      color: white;
    }

    .whatsapp {
      margin-top: 10px;
      display: inline-block;
      background-color: #25D366;
      color: white;
      padding: 10px 20px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
    }

  </style>
</head>
<body>
  <header>
    <h1>Catálogo Apolo Group</h1>
    <p>Calzado, ropa y tecnología al por mayor y al detal</p>
  </header>

  <nav>
    <a href="#calzado">Calzado</a>
    <a href="#ropa">Ropa</a>
    <a href="#tecnologia">Tecnología</a>
  </nav>

  <section class="section" id="calzado">
    <h2>Calzado</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/200x150?text=Tenis+Nike" alt="Tenis Nike">
        <h3>Tenis Nike Air Max</h3>
        <p>$160.000 COP</p>
        <p>Tallas: 37-43</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x150?text=Botas+Timberland" alt="Botas">
        <h3>Botas Timberland</h3>
        <p>$190.000 COP</p>
        <p>Colores: Marrón, Negro</p>
      </div>
    </div>
  </section>

  <section class="section" id="ropa">
    <h2>Ropa</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/200x150?text=Camiseta+Oversize" alt="Camiseta Oversize">
        <h3>Camiseta Oversize</h3>
        <p>$45.000 COP</p>
        <p>Tallas S-M-L</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x150?text=Jeans+Skinny" alt="Jeans">
        <h3>Jeans Skinny</h3>
        <p>$75.000 COP</p>
        <p>Tallas 28-36</p>
      </div>
    </div>
  </section>

  <section class="section" id="tecnologia">
    <h2>Tecnología</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/200x150?text=Auriculares+Bluetooth" alt="Audífonos">
        <h3>Auriculares Bluetooth</h3>
        <p>$70.000 COP</p>
        <p>Modelos disponibles</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x150?text=Smartwatch" alt="Smartwatch">
        <h3>Smartwatch X9</h3>
        <p>$110.000 COP</p>
        <p>Negro y Azul</p>
      </div>
    </div>
  </section>

  <footer>
    <p>Contacto directo por WhatsApp</p>
    <a class="whatsapp" href="https://wa.me/573232135702" target="_blank">💬 Escribir a Apolo</a>
    <p>&copy; 2025 Apolo Group. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
