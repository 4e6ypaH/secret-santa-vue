<template>
  <div id="app">
    <main-page msg="Secret Santa"/>
  </div>
</template>

<script>
import MainPage from './components/MainPage.vue'

export default {
  name: 'App',
  components: {
    MainPage
  }
}
</script>

<style>
#app {
  font-family: Nunito, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  box-sizing:border-box;
}

h1 {
  color: #FBFBFB
}

a { 
  /* text-decoration-color: black; */
  color: #1A1A1A;
}

.mt-2 {
  margin-top: 8px;
}

.mb-2 {
  margin-bottom: 8px;
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

.btn {
  background-color: #F673BB;
  border: 0;
  border-radius: 100px;
  color: #fff;
  font-size: 14px;
  padding: 10px;
  width: 100%;
}
</style>
