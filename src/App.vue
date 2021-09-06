<template>
  <div id="app">
    <img alt="Retarded" src="./assets/retarded.jpg">
    <Index/>
  </div>
</template>

<script>
import Index from './components/index.vue'

export default {
  name: 'App',
  components: {
    Index
  }
}
</script>

<style>
html, body, #app {
  top: 0;
  left: 0;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  position: fixed;
  color: #2c3e50;
  text-align: center;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
img {
  width: 100%;
}
</style>
