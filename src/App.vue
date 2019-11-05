<template>
<div>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
        <HelloWorld msg="Welcome to Your Vue.js App"/>

    <HelloWorld msg="Welcome to Your Vue.js App"/>

  </div>
        <iframe src="https://playcanv.as/p/8NZ92jAY/?overlay=false" />

</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
html{
  background:white;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin-top: 60px;
  background: transparent;
  position:absolute;
  z-index: 1;
    width: 100vw;
  height: 100vh;
}
iframe{

  width: 100vw;
  height: 100vh;
  border: none;
  position:fixed;
  z-index: 0;
  top: 0;
  left: 0;
}
</style>
