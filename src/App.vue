<template>
  <div id="app">
    <div id="forest" alt="Cover Photo"></div>
    
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
  color: #2c3e50;
  margin-top: 60px;
}
#forest {
  height: 1500px;
  background:  url('C:\\Users\\user\\Documents\\Projects\\personal-webpage\\src\\assets\\IrelandForest.jpg') ;
  background-size: cover;
  box-shadow: 25px 25px 50px 0 white inset, -25px -25px 50px 0 white inset; 
  margin-left: auto;
  margin-right: auto;
  width: 70%;
}
</style>
