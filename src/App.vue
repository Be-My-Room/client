<template>
  <img alt="Logo" src="https://hochiminhcity.equatorial.com/wp-content/uploads/sites/7/2014/10/2020-04-15_hehcmc-premier-balcony.jpg">
  <HelloWorld msg="Welcome to Be My Room"/>
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
img {
  height: 500px;
  
}
</style>
