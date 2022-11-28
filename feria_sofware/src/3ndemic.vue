<template>
<div>
    <nav class ="contenedor">
      <img src="./assets/fesw-logo.png" width = "150" alt="">
    </nav>
  </div>
  <div class="proyecto">
      <div class="context">
        <h1>CONTEXTO</h1>
        La cantidad de especies endémicas en Chile que están en alguna clase de peligro ha aumentado a niveles críticos durante los últimos años, provocando que la perdida de biodiversidad se convierta un real problema. Entre sus principales causas se encuentra el desconocimiento de dichas especies y de sus ecosistemas, lo que provoca que cada día más se intervenga dentro de su territorio, ya sea por consciencia o inconsciencia de los humanos.
        Orientado a niños y niñas de la educación básica, 3nDemic busca ser una herramienta para la concientización de este problema, dando a conocer a las especies principales en peligro y las dificultades a las que se exponen día a día, junto a un entorno inmersivo del hábitat de tales espcecies.
        <h1>AUSPICIADORES</h1>
        <img src="./assets/microsoft.png" width="50" style="margin: 5px">
        <img src="./assets/mineduc.png" width="50" style="margin: 5px">
      </div>
      <div class ="info">
        <div class ="image">
          <img src="./assets/3ndemic.png" width="600">
        </div>
        <ul class="datos_proyecto">
          <li> a </li>
          <li><a target="_black" class="record" href="https://3ndemic.feriadesoftware.cl/">https://3ndemic.feriadesoftware.cl/</a></li>
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