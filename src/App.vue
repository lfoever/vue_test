<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <div class="box"></div>
    <Tap />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Tap from "./components/Tap.vue";

export default {
  name: "App",
  components: {
    HelloWorld,

    Tap,
  },
};
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
.box {
  width: 100px;
  height: 100px;
  background-color: #ccc;
}
</style>
