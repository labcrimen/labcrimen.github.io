<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Página Principal</title>
  <style>
    /* Estilos para el layout de la página */
    .container {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
    }

    /* Estilos para las imágenes laterales */
    .side-image {
      width: 15%; /* Ajusta el ancho según lo necesites */
      max-width: 150px; /* Tamaño máximo de la imagen */
    }

    /* Estilos para el contenido central */
    .content {
      width: 70%; /* El contenido central ocupa el 70% del ancho */
      padding: 20px;
    }

    /* Ajuste para dispositivos móviles */
    @media (max-width: 768px) {
      .side-image {
        display: none; /* Oculta las imágenes laterales en pantallas pequeñas */
      }

      .content {
        width: 100%; /* El contenido ocupará todo el ancho en pantallas pequeñas */
      }
    }
  </style>
</head>
<body>

  <!-- Contenedor que agrupa las imágenes y el contenido -->
  <div class="container">

    <!-- Imagen izquierda -->
    <div>
      <img class="side-image" src="left.png" alt="Imagen izquierda">
    </div>

    <!-- Contenido central -->
    <div class="content">
      <h1>Equipo</h1>
      <p><a href="https://labcrimen.github.io/bios/">Bios de los investigadores</a></p>

      <h2>Recursos</h2>
      <div id="recursos">
        <a href="https://labcrimen.github.io/recursos/">Recursos</a>
      </div>

      <h2>Publicaciones</h2>
      <p><a href="https://labcrimen.github.io/publicaciones/">Publicaciones</a></p>

      <div align="right">
        <a href="https://www.ucu.edu.uy/" target="_blank">
          <img src="ucu.png" alt="UCU" width="30%" height="30%">
        </a>
        <a href="https://www.udelar.edu.uy/" target="_blank">
          <img src="udelar.png" alt="Udelar" width="20%" height="20%">
        </a>
      </div>
    </div>

    <!-- Imagen derecha -->
    <div>
      <img class="side-image" src="right.png" alt="Imagen derecha">
    </div>

  </div>

</body>
</html>
