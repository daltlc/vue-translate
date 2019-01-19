<template>
  <div id="app">
    <h1>Welcome to Translation!</h1>
    <Translate msg="Hello"/>
  </div>
</template>

<script>
import Translate from './components/Translate.vue'

export default {
  name: 'app',
  components: {
    Translate
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
