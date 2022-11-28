<template>
<div>
    <nav class ="contenedor">
      <img src="./assets/fesw-logo.png" width = "150" alt="">
    </nav>
  </div>
  <div class="proyecto">
      <div class="context">
        <h1>CONTEXTO</h1>
        La comunicación es la base de todas las relaciones por lo que saber comunicarse es fundamental. Muchas veces en el caso de los estudiantes universitarios, destacando el área científica, sus habilidades blandas no son reforzadas. La única forma de mejorar esto, es enfrentándose a al situación por lo que Arsis nace de esta problemática. A través del uso de la realidad virtual, promete sumergirte en una experiencia realista donde puedas practicar tus habilidades comunicativas sin miedo de equivocarte y cada vez mejorarlas más.
        <h1>AUSPICIADORES</h1>
        <img src="./assets/microsoft.png" width="50" style="margin: 5px">
        <img src="./assets/mineduc.png" width="50" style="margin: 5px">
      </div>
      <div class ="info">
        <div class ="image">
          <img src="./assets/arsis.png" width="600">
        </div>
        <ul class="datos_proyecto">
          <li> a </li>
          <li><a target="_black" class="record" href="https://arsis.feriadesoftware.cl/">https://arsis.feriadesoftware.cl/</a></li>
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