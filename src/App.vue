<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <GridContainer /> 
</template>

<script>
import GridContainer from './components/GridContainer.vue'

export default {
  name: 'App',
  components: {
    GridContainer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
