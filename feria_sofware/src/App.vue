<template>
  <div>
    <nav class ="contenedor">
      <img src="./assets/fesw-logo.png" width = "150" alt="">
      <div class="nav" id="navbarSupportedContent">
              <ul class="lista">
                <li class="nav-item ">
              <a class="nav-link" href="https://www.feriadesoftware.cl/">30º Feria de Software</a>
              </li>
                <li class="nav-item">
              <a class="nav-link" href="https://www.feriadesoftware.cl/historia/">Historia</a>
              </li>
                <li class="nav-item">
              <a class="nav-link" href="https://www.feriadesoftware.cl/versiones-anteriores/">Versiones Anteriores</a>
              </li>
                </ul>
            </div>
    </nav>
    <img src="./assets/Banner.png" alt="30º Feria de Software 2022" width="1350">
  </div>
  
  <div class="row">
              <div class="info" >
                <h5>Abierta a todo público </h5> <!-- presentando <b>pase de movilidad</b></h5 -->
                Transmisión vía streaming por: <a target="_black" class="record" href="https://tv.inf.utfsm.cl/">https://tv.inf.utfsm.cl/</a>
              </div>
              <div class="organiza">Organiza</div>
              <a target="_blank" href="http://www.inf.utfsm.cl/"><img class="imagen" src="https://www.feriadesoftware.cl/wp-content/themes/AA-fesw2017/img/Departamento de Informática_HORIZONTAL_BLANCA COMPLETA.png" width="250"></a>
            </div>
            </template>
    
<script>
export default{
    name: 'app',
    components: {
    }
}
</script>

<style>
body{
  background-color: #162c41;
}
.row {
  display:flex;
  flex-wrap:wrap;
  margin-right: -15px;
  margin-left: -15px;
  background-color: rgb(17,33,49);
}
body {
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: #FFFF;
}
.record{
  color: #007bff;
}
.organiza{
  display: flex;
  margin-left: 40%;
  margin-top: 3%;
  margin-bottom: auto;
  margin-right: 2.5%;
}
.imagen{
  margin-top: 18%;
}
.info{
  margin-left: 2%;
}
.nav{
  display: inline-block;
  margin-left: 50%;
}
.lista{
  display: flex;
  list-style: none;

}
.nav-link{
  padding-right: .5rem;
  padding-left: .5rem;
  display: block;
  padding: .5rem 1rem;
  color: white;
  text-decoration: none;
}
</style>