<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <movie-manager/>npm
  </div>
</template>

<script>
import MovieManager from './components/Dashboard.vue'

export default {
  name: 'app',
  components: {
    MovieManager
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
