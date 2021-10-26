<template>
  <h1>Christmas List</h1>
  <List msg="Welcome to Your Vue.js App"/>
</template>

<script>
import List from './components/List.vue'

export default {
  name: 'App',
  components: {
    List
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
