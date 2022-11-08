<template>
  <div id="app">
    <TextIn/>
  </div>
</template>

<script>
import TextIn from './components/TextIn.vue'

export default {
  name: 'app',
  components: {
    TextIn
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
