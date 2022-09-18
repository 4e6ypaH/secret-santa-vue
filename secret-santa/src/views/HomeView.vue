<template>
  <div class="home">
    <MainPage msg="Secret Santa"/>
  </div>
</template>

<script>
// @ is an alias to /src
import MainPage from '@/components/MainPage.vue'

export default {
  name: 'HomeView',
  components: {
    MainPage
  }
}
</script>
