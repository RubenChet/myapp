<template>
  <Navbar />
  <Main />
</template>

<script>
import Navbar from './components/Navbar.vue'
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Main,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>



