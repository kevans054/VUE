
<template>
  <div id="app">
    <vue-menu></vue-menu>
    <vue-new-header></vue-new-header>
    <HelloWorld msg="Assignment W13A"/>
    <vue-new-body></vue-new-body>
    <vue-side-panel></vue-side-panel>
    <vue-meet-dev></vue-meet-dev>
    <vue-meet-team></vue-meet-team>
    <vue-footer></vue-footer>
  </div>
 
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import VueMenu from './components/Menu.vue'; //step 1. import the menu component
import VueNewHeader from './components/Header.vue';
import VueNewBody from './components/Body.vue';
import VueSidePanel from './components/Sidepanel.vue';
import VueMeetDev from './components/MeetDev.vue';
import VueMeetTeam from './components/MeetTeam.vue';
import VueFooter from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    HelloWorld, 
    VueMenu, //step 2. register the component
    VueNewHeader,
    VueNewBody,
    VueFooter,
    VueSidePanel,
    VueMeetDev,
    VueMeetTeam
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
