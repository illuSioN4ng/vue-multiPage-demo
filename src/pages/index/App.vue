<template>
  <div id="app">
    index
    <img src="../../assets/logo.png">
    <HelloWorld/>
    <my-test></my-test>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld'
import test from '@/modules/test/test'

export default {
  name: 'app',
  components: {
    HelloWorld,
    'my-test': test
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
