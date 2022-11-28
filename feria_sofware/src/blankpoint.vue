<template>
<div>
    <nav class ="contenedor">
      <img src="./assets/fesw-logo.png" width = "150" alt="">
    </nav>
  </div>
  <div class="proyecto">
      <div class="context">
        <h1>CONTEXTO</h1>
        El sesgo de los medios masivos de comunicación es algo latente y que cada vez toma más fuerza a medida que la política se hace relevante en el nuevo contexto social que vivimos hoy en día. Diversos estudios tratan cómo el exceso de sesgo político puede sesgar incluso los hechos en pos de un fin político.
        Los medios de comunicación con un marcado sesgo ideológico suelen omitir ciertos aspectos de una noticia, o la redactan de una manera que se adecue a su relato. El ciudadano común no está al pendiente de estas sutilezas, por lo que es fácilmente influenciable por el sesgo al que estuvo expuesto, logrando imponer una idea sesgada sobre el hecho noticioso.
        <h1>AUSPICIADORES</h1>
        <img src="./assets/microsoft.png" width="50" style="margin: 5px">
        <img src="./assets/mineduc.png" width="50" style="margin: 5px">
      </div>
      <div class ="info">
        <div class ="image">
          <img src="./assets/blankpoint.png" width="600">
        </div>
        <ul class="datos_proyecto">
          <li> a </li>
          <li><a target="_black" class="record" href="https://blankpoint.feriadesoftware.cl/">https://blankpoint.feriadesoftware.cl/</a></li>
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