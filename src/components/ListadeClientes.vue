<template>
  <div>    
    <label>Lista de Clientes</label>
    <select name="ListaClientes" id="ListaClientes">
      <option value="cliente1">Selecione</option>
      <option value="cliente1">Petrobras</option>
      <option value="cliente2">Vale do Rio Doce</option>
      <option value="cliente3">Transpetro</option>
    </select>
 
  </div>
  
</template>

<script>
export default {
  name: 'ListadeClientes',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

label {
  color: #42b983;
  font-size: 14px;
}
select{
  color: #b94642;
}
</style>
