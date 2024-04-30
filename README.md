<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hoja de Vida</title> 
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f2f2f2;
    }
    #container {
      max-width: 800px;
      margin: 20px auto;
      background-color: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    h1, h2 {
      text-align: center;
    }
    img {
      display: block;
      margin: 0 auto;
      width: 150px;
      height: auto;
      border-radius: 50%;
    }
    .section {
      margin-bottom: 20px;
    }
    .section h2 {
      border-bottom: 2px solid #333;
      padding-bottom: 5px;
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    li {
      margin-bottom: 10px;
    }
    form {
      margin-top: 20px;
    }
    label {
      display: block;
      margin-bottom: 5px;
    }
    input[type="text"], input[type="tel"] {
      width: 100%;
      padding: 8px;
      margin-bottom: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    input[type="submit"] {
      background-color: #007bff;
      color: #fff;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
    }
    input[type="submit"]:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

<div id="container">
  <header>
    <h1>Michael Santiago Osma Castillo</h1>
    <img src="avatar.jpg" alt="Foto de perfil">
  </header>

  <div class="section">
    <h2>Información Básica</h2>
    <ul>
      <li>Fecha de Nacimiento: 06/06/2005</li>
      <li>Dirección: Bogota, Colombia</li>
      <li>Email: santicas2005@gmail.com</li>
      <li>Teléfono: +57 3138759498</li>
    </ul>
  </div>

  <div class="section">
    <h2>Estudios</h2>
    <ul>
      <li>Bachiller, Colegio de la presentacion, 2010- 2022</li>
    </ul>
  </div>

  <div class="section">
    <h2>Experiencia Laboral</h2>
    <ul>
      <li>Nombre del Puesto, Empresa, Fecha de inicio - Fecha de finalización</li>
      <li>Nombre del Puesto, Empresa, Fecha de inicio - Fecha de finalización</li>
    </ul>
  </div>

  <div class="section">
    <h2>Contacto</h2>
    <form action="#" method="post">
      <label for="email">Correo Electrónico: santicas2005@gmail.com</label>
      <input type="text" id="email" name="email" required>
      <label for="phone">Número de Teléfono: 3138759498</label>
      <input type="tel" id="phone" name="phone" required>
      <input type="submit" value="Enviar">
    </form>
  </div>
</div>

</body>
</html>

