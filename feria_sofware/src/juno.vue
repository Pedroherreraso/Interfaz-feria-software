<template>
<div>
    <nav class ="contenedor">
      <img src="./assets/fesw-logo.png" width = "150" alt="">
    </nav>
  </div>
  <div class="proyecto">
      <div class="context">
        <h1>CONTEXTO</h1>
        Tablón de Anuncios Digital
        Permite categorizar, organizar y difundir los mensajes públicos realizados por la comunidad de manera instantánea, informando debidamente toda clase de noticias, eventos e indicaciones.
        Facilitación de Productos
        Ofrece una herramienta focalizada en la venta y arriendo de productos, automatizando la interacción entre ambas personas y agilizando la compra, el arriendo y la eventual devolución del producto.
        Prestación de Servicios
        Cuenta con una función que permite a cualquier miembro de la comunidad ofrecer y solicitar uno o más servicios, brindándoles una intuitiva herramienta que permita facilitar la coordinación entre ambos miembros.
        <h1>AUSPICIADORES</h1>
        <img src="./assets/microsoft.png" width="50" style="margin: 5px">
        <img src="./assets/mineduc.png" width="50" style="margin: 5px">
      </div>
      <div class ="info">
        <div class ="image">
          <img src="./assets/juno.png" width="600">
        </div>
        <ul class="datos_proyecto">
          <li> a </li>
          <li><a target="_black" class="record" href="https://junoapp.feriadesoftware.cl/">https://junoapp.feriadesoftware.cl/</a></li>
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