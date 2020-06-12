<template>
  <div id="app">
    <Cpt count="0"/>
  </div>
</template>

<script>
import Cpt from './components/Cpt'

export default {
  components: {
    Cpt
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
}
</style>
