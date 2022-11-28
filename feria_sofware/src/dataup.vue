<template>
<div>
    <nav class ="contenedor">
      <img src="./assets/fesw-logo.png" width = "150" alt="">
    </nav>
  </div>
  <div class="proyecto">
      <div class="context">
        <h1>CONTEXTO</h1>
        A medida que pasan los años el cambio climático comienza a ser un tema más importante, y desde todas las áreas se buscan soluciones para frenar el avance de este, la industria de los eventos no es una excepción. Cada vez son más las empresas productoras que buscan tener un sello verde junto a su nombre y ser un referente para las demás, sin embargo, no es fácil mitigar la huella de carbono que los eventos producen, dado que dentro de los cálculos hay información que depende de los asistentes y es la más difícil de obtener.
        Frente a esto nace la idea de Data Up, una aplicación con la que los usuarios podrán responder encuestas, entregando datos que serán utilizados para el cálculo del impacto ambiental de los eventos, con los cálculos hechos las empresas podrán informarse de su huella de carbono y tomar cartas para mitigar esta.
        <h1>AUSPICIADORES</h1>
        <img src="./assets/microsoft.png" width="50" style="margin: 5px">
        <img src="./assets/mineduc.png" width="50" style="margin: 5px">
      </div>
      <div class ="info">
        <div class ="image">
          <img src="./assets/dataup.png" width="600">
        </div>
        <ul class="datos_proyecto">
          <li> a </li>
          <li><a target="_black" class="record" href="https://dataup.feriadesoftware.cl/">https://dataup.feriadesoftware.cl/</a></li>
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