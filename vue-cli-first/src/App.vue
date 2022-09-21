<template>
  <div id="app">
    <AppTitle/>
    <JumboTron/>

  </div>


</template>

<script>
import AppTitle from './components/AppTitle.vue'
import JumboTron from './components/JumboTron.vue'

export default {
  name: 'App',
  components: {
    AppTitle,
    JumboTron
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
