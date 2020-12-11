<template>
  <div id="app">
    <vue-menu></vue-menu>  
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Hello world"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import VueMenu from './components/Menu.vue' //step 1. import the menu component


export default {
  name: 'App',
  components: {
    HelloWorld, 
    VueMenu //step 2. register the menu component
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
