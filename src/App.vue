<template>
  <img v-if="true" alt="Vue logo" src="./assets/logo.png"> 
  <img v-else alt="Vue logo" src="./assets/logo.png">
<!-- <li v-for="item in items"> {{item.mesage}}</li> -->
  <HelloWorld msg="Welcome to Your Vue.js classe 1- "/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },

  data(){
    return {
      items: [{mesage: "for"}, {mesage: "bar"}]
    }

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
