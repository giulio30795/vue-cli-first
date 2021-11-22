<template>

  <div id="app">
      <Titolo />
      <Jumbotron />
  </div>

</template>

<script>
import Titolo from './components/Titolo.vue'
import Jumbotron from './components/Jumbotron.vue'
export default {
  name: 'App',
  components: {
    Titolo,
    Jumbotron,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
