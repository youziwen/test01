<template>
  <h1>test02</h1>
  <img alt="Vue logo" src="./assets/logo_2.0.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
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
  img{
    width: 10%;
    height: 10%;
  }
</style>
