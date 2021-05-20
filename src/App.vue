<template>
  <div id="app" style="margin: left 250px;">
    <head_tipp/>
    <home/>
    <inicioaap name_user="Tomas Ipperi" img_logo="logo" project_name="Tipp Market"/>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue';
import inicioaap from './components/inicioaap.vue';
import home from './components/home.vue';
import head_tipp from './components/head_tipp.vue';





export default {
  name: 'App',
  components: {
    head_tipp,inicioaap,home
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
  /* margin-top: 60px; */
}
</style>
