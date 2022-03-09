<template>
  <div id="app">
    <TitleComponent />
    <JumboComponent />
  </div>
</template>

<script>
import TitleComponent from './components/TitleComponent.vue'
import JumboComponent from './components/JumboComponent.vue'

export default {
  name: 'App',
  components: {
    TitleComponent,
    JumboComponent
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
