<template>
  <index/>
</template>

<script>
import index from './components/index.vue'

export default {
  name: 'App',
  components: {
    index
  }
}
</script>

<style>
body{
  background: hsl(212, 45%, 89%);
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
