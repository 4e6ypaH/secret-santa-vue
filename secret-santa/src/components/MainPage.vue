<template>
  <div class="wrapper">
    <h1>{{ msg }}</h1>
    <img class="mt-2 mb-12" alt="Santa logo" src="../assets/logo.png">
    <button @click="toCreateListPage" class="btn mb-8">Создать список</button>
    <div>
      <button class="rules-button" @click="toRulesInfoPage">
        <span class="rules-button-text">Правила игры</span>
        </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainPage',
  props: {
    msg: String
  },
  methods: {
    toCreateListPage() {
      this.$router.push({
        name: 'create-list'
      })
    },
    toRulesInfoPage() {
      this.$router.push({
        name: 'rules-info'
      })
    }
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

.btn {
  background-color: #F673BB;
  border: 0;
  border-radius: 100px;
  color: #fff;
  font-size: 14px;
  padding: 10px;
  width: 100%;
}

a { 
  color: #1A1A1A;
}

.mb-4 {
  margin-bottom: 16px;
}

.mb-6 {
  margin-bottom: 24px;
}

.mb-8 {
  margin-bottom: 32px;
}

.mb-12 {
  margin-bottom: 48px;
}

.mb-16 {
  margin-bottom: 64px;
}

.rules-button {
  background-color: inherit;
  border: 0;
}

.rules-button-text {
  text-decoration: underline;
}

</style>
