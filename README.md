<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Niurka</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body, html {
      height: 100%;
      font-family: 'Segoe UI', sans-serif;
    }

    .contenedor {
      display: flex;
      height: 100vh;
    }

    .contenido {
      width: 60%;
      background-color: rgba(255, 255, 255, 0.95);
      padding: 40px;
      overflow-y: auto;
    }

    .imagen-derecha {
      width: 40%;
      background-image: url('fondo.jpg');
      background-size: cover;
      background-position: center;
    }

    header {
      background-color: #ffb6c1;
      padding: 60px 20px;
      text-align: center;
      border-radius: 20px;
    }

    header h1 {
      font-size: 3em;
      color: white;
    }

    main {
      padding: 40px 20px;
      text-align: center;
    }

    main h2 {
      font-size: 2em;
      color: #a83c6c;
      margin-bottom: 15px;
    }

    main p {
      font-size: 1.2em;
      color: #5a2b51;
      max-width: 500px;
      margin: auto;
    }

    footer {
      background-color: #ffe6ef;
      text-align: center;
      padding: 15px;
      color: #5a2b51;
      font-size: 0.9em;
      margin-top: 40px;
      border-radius: 20px;
    }
  </style>
</head>
<body>
  <div class="contenedor">
    <div class="contenido">
      <header>
        <h1>Niurka</h1>
      </header>
      <main>
        <h2>Bienvenidos</h2>
        <p>Esta es mi página de inicio. Pronto sabrás más sobre mi proyecto.</p>
      </main>
      <footer>
        <p>© 2025 Niurka. Todos los derechos reservados.</p>
      </footer>
    </div>
    <div class="imagen-derecha"></div>
  </div>
</body>
</html>
