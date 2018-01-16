<template>
  <div id="app">
    this is test module
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld'

export default {
  name: 'test',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>
#app {
  color: red;
}
</style>
