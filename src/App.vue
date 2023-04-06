<template>
  <HelloWorld msg="Welcome OESB 2023"/>
  <HelloWorld msg="Welcome OESB 2023"/>
  <TestHello msg="Welcome OESB 2023"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TestHello from './components/Test.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,TestHello
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
