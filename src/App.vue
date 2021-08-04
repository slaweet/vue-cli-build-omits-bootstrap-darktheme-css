<style lang="css" src="bootstrap/dist/css/bootstrap.css"></style>
<style lang="css" src="bootstrap-darkmode/css/darktheme.css"></style>

<template>
  <div id="app" >
    <img alt="Vue logo" src="./assets/logo.png">
    <div class="card card-body">Test card</div>
    <div class="alert alert-warning">Test alert</div>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
