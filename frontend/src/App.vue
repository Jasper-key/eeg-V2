<template>
  <div id="app">
    <mains></mains>
  </div>
</template>

<script>
import Mains from './components/Mains';
export default {
  name: 'App',
  components: {
    Mains,
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 100%;
  height: 100%;
}
</style>
