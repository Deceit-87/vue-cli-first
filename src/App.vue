<template>
  <div id="app">
    <TitleFirst/>
    <JumboTron/>
    

  </div>
</template>

<script>
import JumboTron from './components/JumboTron.vue'
import TitleFirst from './components/TitleFirst.vue'


export default {
  name: 'App',
  components: {
    TitleFirst,
    JumboTron,
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
