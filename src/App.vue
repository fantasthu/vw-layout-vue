<template>
  <div id="app">
    <img src="./assets/logo.png">
    <mt-button type="default" size="large" class="mt-button">default</mt-button>
    <router-view/>
  </div>
</template>

<script>
import { Button, Cell } from 'mint-ui'
export default {
  name: 'App',
  components: {
    'mt-button': Button
  }
}
</script>

<style>
html,
body {
  padding: 0;
  margin: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.mt-button {
  font-size: 32px;
  height: 100px;
}
</style>
