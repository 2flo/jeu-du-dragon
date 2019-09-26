<template>
  <div id="app">
    <duel/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import duel from './components/duel.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    duel
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
