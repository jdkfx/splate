<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
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
  color: #2c3e50;
  margin-top: 60px;
  position: relative;
  overflow: hidden;
  z-index: 0;
}

body::before {
  content: '';
  position: absolute;
  background-image: url('/src/assets/images/stageL/Vss_Yunohana.png');
  background-size: cover;
  filter: blur(5px);
  top: -3px;
  bottom: -3px;
  left: -3px;
  right: -3px;
  z-index: -1;
}
</style>
