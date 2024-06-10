<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <PetShopAmigao msg="Bem vindo ao Pet Shop Amigão Vue.js" />
    <ListaDeClientesPetShop />
  </div>
</template>
<script>
import PetShopAmigao from './components/PetShopAmigao.vue';
import ListaDeClientesPetShop from './components/ListadeClientesPetShop.vue';
export default {
  name: 'app',
  components: {
    PetShopAmigao,
    ListaDeClientesPetShop,
     }
     
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>