<template>
  <div>
    <label for="listaDeClientesPetShop">Lista de Clientes do Pet Shop</label>
    <select v-model="clienteSelecionado" name="listaDeClientesPetShop" id="listaDeClientesPetShop">
      <option value="cliente1">João</option>
      <option value="cliente2">Paulo</option>
      <option value="cliente3">Leda</option>
      <option value="cliente4">Maria</option>
    </select>
    <p>Cliente selecionado: {{ clienteSelecionado }}</p> <!-- Mostra o cliente selecionado -->
  </div>
</template>

<script>
export default {
  name: 'ListaDeClientesPetShop',
  data() {
    return {
      clienteSelecionado: 'cliente1' 
    };
  }
};
</script>

<style scoped>
label {
  color: #4244b9;
  font-size: 14px;
}

select {
  color: #010400;
  font-size: 14px;
}
</style>