<template>
  <div>
    <Navbar/>
    <Body/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Body from './components/Body.vue'


export default {
  name: 'App',
  components: {
    Navbar,
    Body

    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  
  
}
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}
</style>
