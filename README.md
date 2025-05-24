<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />
    <link rel="stylesheet" href="CSS/styles.css" />
  </head>
  <!DOCTYPE html>
<html lang="es">
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>OK de Envío QC</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 60px;
      background-color: #f5faff;
    }
    h1 {
      color: #2c3e50;
    }
    .dato {
      font-size: 1.4em;
      margin: 15px;
    }
  </style>
</head>
<body>

  <h1>✅ OK de Envío QC</h1>

  <div class="dato"><strong>Nombre:</strong> M.Muñoz</div>
  <div class="dato"><strong>Fecha:</strong> <span id="fecha"></span></div>

  <script>
    const hoy = new Date();
    const opciones = { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' };
    const fechaActual = hoy.toLocaleDateString("es-ES", opciones);
    document.getElementById("fecha").textContent = fechaActual;
  </script>

</body>
</html>
