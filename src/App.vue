<template>
  <div id="app">
    <TitleFirst/>
    <JumboTron/>
    

  </div>
</template>

<script>
import TitleFirst from './components/TitleFirst.vue'
import JumboTron from './components/TitleFirst.vue'


export default {
  name: 'App',
  components: {
    JumboTron ,
    TitleFirst
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
