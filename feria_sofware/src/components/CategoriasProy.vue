<template>
    <div>
        <div id="contenedor">
            <div id="cat">
                <h1>Categorias</h1>
                <div id="elegir">
                    <h2>Inteligencia Artificial</h2>
                </div>
                <div id="elegir">
                    <h2>Transformación Digital y Social</h2>
                </div>
            </div>
            <div id="proy">
                <div id="encabezado">
                    <h1>Inicio</h1>
                </div>
                <div id="padre">
                    <div id="imagen">
                        <div id="padrefoto" >
                            <a href="http://localhost:8080/">
                                <img id="foto" src="../assets/arsis.jpg">
                            </a>
                            </div>
                        <div id="titulo">
                            <h4>Arsis</h4>
                        </div>
                        <div id="opciones">
                            <p class="direccion">Video </p>
                            <p class="direccion">Mas Información</p>
                            <p class="direccion"><a href="https://www.google.com/webhp?source=search_app">Compartir</a></p>
                        </div>
                        <div id="descripcion">
                            <p style="text-align:justify">Breve descripción: BlankPoint es una extensión y aplicación web que mediante Inteligencia Artificial y CrowdSourcing detecta el sesgo político.</p>
                        </div>
                    </div>
                    <div id="imagen">
                        <div id="padrefoto" >
                            <a href="http://localhost:8080/">
                                <img id="foto" src="https://www.adslzone.net/app/uploads-adslzone.net/2019/04/borrar-fondo-imagen.jpg">
                            </a>
                            </div>
                        <div id="titulo">
                            <h4>Activate</h4>
                        </div>
                        <div id="opciones">
                            <p class="direccion">Video </p>
                            <p class="direccion">Mas Información</p>
                            <p class="direccion"><a href="https://www.google.com/webhp?source=search_app">Compartir</a></p>
                        </div>
                        <div id="descripcion">
                            <p style="text-align:justify">Breve descripción: Activate es una aplicación móvil que simula ser un gimnasio para tu cerebro. Por medio de Inteligencia Artificial.</p>
                        </div>
                    </div>
                    

    
                </div>
                <div id="padre">
                    <div id="imagen">
                        <div id="padrefoto" >
                            <a href="http://localhost:8080/">
                                <img id="foto" src="https://www.adslzone.net/app/uploads-adslzone.net/2019/04/borrar-fondo-imagen.jpg">
                            </a>
                            </div>
                        <div id="titulo">
                            <h4>Binmo</h4>
                        </div>
                        <div id="opciones">
                            <p class="direccion">Video </p>
                            <p class="direccion">Mas Información</p>
                            <p class="direccion"><a href="https://www.google.com/webhp?source=search_app">Compartir</a></p>
                        </div>
                        <div id="descripcion">
                            <p style="text-align:justify">Breve descripción: Sistema de detección temprana de bullying mediante análisis de video en tiempo real para instituciones educacionales.</p>
                        </div>
                    </div>
                    <div id="imagen">
                        <div id="padrefoto" >
                            <a href="http://localhost:8080/">
                                <img id="foto" src="https://www.adslzone.net/app/uploads-adslzone.net/2019/04/borrar-fondo-imagen.jpg">
                            </a>
                            </div>
                        <div id="titulo">
                            <h4>BlackPoint</h4>
                        </div>
                        <div id="opciones">
                            <p class="direccion">Video </p>
                            <p class="direccion">Mas Información</p>
                            <p class="direccion"><a href="https://www.google.com/webhp?source=search_app">Compartir</a></p>
                        </div>
                        <div id="descripcion">
                            <p style="text-align:justify">Breve descripción: BlankPoint es una extensión y aplicación web que mediante Inteligencia Artificial y CrowdSourcing detecta el sesgo político.</p>
                        </div>
                    </div>
                    

    
                </div>
                
                

            </div>
            
        </div>
    </div>
</template>
<script>
export default {
    name: 'CategoriasProy'
}
</script>

<style scoped>

    #contenedor{
        width:auto;
        margin-left: 10px;
        margin-right: 10px;
        margin-bottom: 10px;
    }
    #proy {
        background-color:#2c3e50;
        float:left;
        height:800px;
        padding: auto;
        width:80%;
        justify-content: center;
        margin-left: 1%;
        border-radius: 5px ;
      }
      #cat {
        background-color:#23507c;
        float:left;
        height:800px;
        width:19%;
        border-radius: 5px ;
        margin-bottom: 10px;
      }
      #imagen{
        margin:0 auto;
        background-color: rgba(224, 14, 14, 0);
        height:350px;
        width: 450px;
        display:inline-block;
        margin-left: 7%;
        margin-right: 7%;
        margin-top: 10px;

        
      }
      #foto{
        width: 100%;
        height: 100%;
        border-radius: 3px ;
        
      }
      #padre{
        background-color: #65f70400;
        
        
      }
      #elegir{
        background-color: #0080ff00;
        margin-top: 240px;
        margin-left: 10px;
        margin-right: 10px;
        border-radius: 5px ;
        
      }
      #encabezado{
        background-color: #ffffff00;
        margin-bottom: 30px;
        margin-left: 13%;
        text-align: left;
      }
      #descripcion{
        background-color: #ff000000;
        height: 23%;
    
    
        
        
      }
      #padrefoto{
        background-color:rgba(255, 255, 255, 0);
        height: 60%;
      }
      #opciones{
        background-color: #ffffff00;
        height: 10%;
        text-align: left;
        
      }
      .direccion{
        
        display: inline-block;
        margin-right: 20px;
      }
      #titulo{
        background-color: #ffffff00;
        height: 7%;
        text-align: left;
        
      }

</style>
