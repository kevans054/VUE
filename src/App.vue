<template>
  <div id="app">
    <vue-header></vue-header>
    <vue-menu></vue-menu>  
    <HelloWorld msg="Assignment W13A"/>
    <vue-newbody></vue-newbody>
    <vue-footer></vue-footer>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import VueMenu from './components/Menu.vue' //step 1. import the menu component
import VueFooter from './components/Footer.vue'
import Vuenewbody from './components/Body.vue'
import VuenewHeader from './components/Header.vue'


export default {
  name: 'App',
  components: {
    HelloWorld, 
    VueMenu, //step 2. register the component
    VueFooter,
    Vuenewbody,
    VuenewHeader
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
