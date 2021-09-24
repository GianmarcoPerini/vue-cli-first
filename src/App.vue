<template>
  <div id="app">
<page/>
  </div>
</template>

<script>
import page from './components/page.vue'

export default {
  name: 'App',
  components: {
    page,
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
