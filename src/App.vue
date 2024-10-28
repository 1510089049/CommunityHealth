<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HealthComp></HealthComp>
  </div>
</template>
<script>

import HealthComp from './components/firstComponet.vue'

export default {
  name: 'App',
  components: {
    HealthComp
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
