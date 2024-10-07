<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Página Principal</title>
  <style>
    /* Contenedor para las imágenes laterales */
    .left-image, .right-image {
      position: fixed;
      top: 0;
      width: 10%; /* Ajusta el tamaño según lo necesites */
      height: 100%;
      background-size: cover;
    }

    .left-image {
      left: 0;
      background-image: url('left.png'); /* Cambia por la ruta de tu imagen */
    }

    .right-image {
      right: 0;
      background-image: url('right.png'); /* Cambia por la ruta de tu imagen */
    }
    
    /* Para evitar que las imágenes laterales tapen el contenido */
    body {
      margin-left: 12%; /* Ajusta este margen si es necesario */
      margin-right: 12%;
    }
  </style>
</head>
<body>
  
  <!-- Imágenes laterales -->
  <div class="left-image"></div>
  <div class="right-image"></div>

<!-- ## Presentación del proyecto ## -->

<!-- LO ESCRIBEN LOS INVESTIGADORES -->

### Equipo ###

[Bios de los investigadores](https://labcrimen.github.io/bios/)

### Recursos ###

<div id="recursos">
    [Recursos](https://labcrimen.github.io/recursos/)
</div>

### Publicaciones ###

[Publicaciones](https://labcrimen.github.io/publicaciones/)
 
<div align="right">
  <a href="https://www.ucu.edu.uy/" target="_blank">
    <img src="ucu.png" alt="UCU" width="30%" height="30%" />
  </a>
  <a href="https://www.udelar.edu.uy/" target="_blank">
    <img src="udelar.png" alt="Udelar" width="20%" height="20%" />
  </a>
</div>                               
