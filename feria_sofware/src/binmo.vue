<template>
<div>
    <nav class ="contenedor">
      <img src="./assets/fesw-logo.png" width = "150" alt="">
    </nav>
  </div>
  <div class="proyecto">
      <div class="context">
        <h1>CONTEXTO</h1>
        Una de las principales preocupaciones que los colegios deben tener, en vista de un desarrollo sostenible, es garantizar la seguridad física y emocional de sus estudiantes con el fin de proveerles un ambiente adecuado para el aprendizaje. Dentro de las principales amenazas y probablemente tratándose de una de las más difíciles de detectar se encuentra el bullying.
        <h1>AUSPICIADORES</h1>
        <img src="./assets/microsoft.png" width="50" style="margin: 5px">
        <img src="./assets/mineduc.png" width="50" style="margin: 5px">
      </div>
      <div class ="info">
        <div class ="image">
          <img src="./assets/binmo.png" width="600">
        </div>
        <ul class="datos_proyecto">
          <li> a </li>
          <li><a target="_black" class="record" href="https://binmo.feriadesoftware.cl/index.html">https://binmo.feriadesoftware.cl/index.html</a></li>
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