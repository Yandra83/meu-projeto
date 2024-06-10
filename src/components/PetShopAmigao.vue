<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <h3>Menu</h3>
    <ul>
      <li><a href="link1" target="_blank" rel="noopener">Opção 1</a></li>
      <li><a href="link2" target="_blank" rel="noopener">Opção 2</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'PetShopAmigao',
  props: {
    msg: String
  }
};
</script>

<style scoped>
.hello {
  text-align: center;
}

h3 {
  margin-top: 40px;
}

a {
  color: #0cefc2;
}
</style>