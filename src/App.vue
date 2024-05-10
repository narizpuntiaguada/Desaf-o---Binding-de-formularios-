<template>
  <div id="app">
    <h1>Registro de tarjeta de crédito</h1>
    
    <CardTarjeta/>
   
  </div>
</template>

<script>
import CardTarjeta from "./components/CardTarjeta.vue"
export default {
  name: 'App',
  components: {
    CardTarjeta
  }
}
</script>

<style>
     h1 {
      text-align: center;
     }
</style>