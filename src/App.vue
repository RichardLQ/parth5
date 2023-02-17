<template>
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <IndexInfo />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import IndexInfo from './components/index/IndexInfo.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    IndexInfo
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
}
</style>
