<template>
  <div id="app">
    <nav>
        Здесь будет навбар
    </nav>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Nunito, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
  background-color: green;
  color: yellow;
}
</style>
