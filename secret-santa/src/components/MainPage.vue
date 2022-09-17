<template>
  <div class="wrapper">
    <h1>{{ msg }}</h1>
    <img class="mt-2 mb-12" alt="Santa logo" src="../assets/logo.png">
    <button class="btn mb-8">Создать список</button>
    <a href="">Правила игры</a>
  </div>
</template>

<script>
export default {
  name: 'MainPage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.wrapper {
  padding: 15px;
  background: rgb(181,188,255);
  background: linear-gradient(90deg, rgba(181,188,255,1) 0%, rgba(205,210,255,1) 100%);
}

</style>
