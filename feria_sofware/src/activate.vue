<template>
<div>
    <nav class ="contenedor">
      <img src="./assets/fesw-logo.png" width = "150" alt="">
    </nav>
  </div>
  <div class="proyecto">
      <div class="context">
        <h1>CONTEXTO</h1>
        El incremento exponencial de la tecnología nos ha dado un sin fin de nuevas facilidades, pero al mismo tiempo se generó una gran dependencia hacia ellas. Esto, sumado a la pandemia, ha provocado en las personas un deterioro sostenido en el ámbito de la memoria, y hoy en día está repercutiendo en el mundo educacional, laboral, e incluso en la vida cotidiana.Por esto, presentamos ACTIVATE, una aplicación móvil cuyo objetivo principal es disminuir el deterioro de la memoria de sus usuarios mediante sesiones de entrenamiento guiado. Estas sesiones estarán compuestas por una serie de ejercicios interactivos en el formato de minijuegos, donde el usuario trabajará la memoria desde distintos ángulos. Posteriormente, el usuario contará con retroalimentación y consejos para seguir mejorando su entrenamiento.
        <h1>AUSPICIADORES</h1>
        <img src="./assets/microsoft.png" width="50" style="margin: 5px">
        <img src="./assets/mineduc.png" width="50" style="margin: 5px">
      </div>
      <div class ="info">
        <div class ="image">
          <img src="./assets/activate.png" width="600">
        </div>
        <ul class="datos_proyecto">
          <li> a </li>
          <li><a target="_black" class="record" href="https://activate.feriadesoftware.cl/">https://activate.feriadesoftware.cl/</a></li>
          <li><h2>Proyecto Activo</h2></li>
        </ul>
        <span>Comentar sobre este proyecto:</span>
        <p style="white-space: pre-line;">{{ message }}</p>
        <textarea v-model="message" placeholder="Escriba su comentario"></textarea>
      </div>
  </div>

</template>

<style>
body {
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: #FFFF;
  background-color: #162c41;
}

.proyecto {
  display: flex;
  margin: 50px;
}

.proyecto .info{
  margin: 50px;
}

</style>