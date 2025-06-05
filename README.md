<!Mi perfil html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mi primera página</title>
  <style>
    body {
      background-color: #e6f0fa;
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 800px;
      margin: 40px auto;
      background-color: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    }

    h1 {
      text-align: center;
      color: #1a73e8;
      margin-bottom: 10px;
    }

    h2 {
      text-align: center;
      color: #333;
      margin-top: 0;
    }

    img {
      display: block;
      max-width: 200px;
      height: auto;
      border-radius: 50%;
      margin: 20px auto;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    p {
      color: #444;
      font-size: 18px;
      line-height: 1.6;
      text-align: justify;
    }

    .contacto {
      margin-top: 30px;
      padding-top: 20px;
      border-top: 1px solid #ccc;
    }

    .contacto h3 {
      color: #1a73e8;
      text-align: center;
    }

    .contacto ul {
      list-style: none;
      padding: 0;
      font-size: 16px;
      color: #333;
      text-align: center;
    }

    .contacto ul li {
      margin: 10px 0;
    }

    a {
      color: #1a73e8;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Mi primera página</h1>
    <h2>¡Hola mundo!</h2>

    <!-- Imagen de perfil -->
    <img src="Imagenes/itca-carrera-002.jpg" alt="Imagen profesional de Pamela Maza">

    <p>
      Bienvenido a mi primera página web. Me llamo Pamela Maza y soy estudiante de Administración de Empresas con pasión por el comercio y el emprendimiento. Desde joven he estado involucrado en ventas, comenzando con la venta de pequeños articulos.
    </p>

    <p>
      Mi objetivo es conectar con las personas, entender lo que necesitan y ayudarlas a encontrar soluciones efectivas. Creo firmemente en productos para ofrecer calidad, un servicio excelente y construir relaciones de confianza a largo plazo.
    </p>

    <!-- Sección de contacto -->
    <div class="contacto">
      <h3>Contáctame</h3>
      <ul>
        <li><strong>Email:</strong> <a href="pamela:rich.emprende@gmail.com">pamela.emprende@gmail.com</a></li>
        <li><strong>Teléfono / WhatsApp:</strong> <a href="https://wa.me/593999999999" target="_blank">+593 99 999 9999</a></li>
        <li><strong>Instagram:</strong> <a href="https://instagram.com/rich_emprende" target="_blank">@rich_emprende</a></li>
        <li><strong>Ubicación:</strong> Loja, Ecuador</li>
      </ul>
    </div>
  </div>
</body>
</html>
