<template>
    <Pagina_Inicial/>
  </template>
    
<script>
import Pagina_Inicial from './components/Pagina_Inicial';
export default{
    name: 'app',
    components: {
        Pagina_Inicial,
    }
}
</script>

<style>
body{
  margin: 0; 
  padding: 0;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #162C41;
  min-height: 100vh;
}
</style>