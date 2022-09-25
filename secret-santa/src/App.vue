<template>
  <div id="app">
    <nav>
        Здесь будет навбар
    </nav>
    <router-view/>
  </div>
</template>

<style>
.wrapper * {
  box-sizing: border-box;
  padding: 0 8px;
}

#app {
  font-family: Nunito, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

.px-2 {
  padding: 0 8px;
}

#app h1 {
  text-align: center;
  margin: 0px;
}

#app h2 {
  font-weight: 600;
  font-size: 16px;
}

nav {
  padding: 30px;
  background-color: green;
  color: yellow;
  text-align: center;
}

.content-page {
  background-color: #E2E5FF;
  padding: 16px 0;
}
</style>
