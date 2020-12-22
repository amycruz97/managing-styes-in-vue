<template>
  <div>
    <Navbar/>
    <Body/>
    <Footer/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Body from './components/Body.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Navbar,
    Body,
    Footer,

    
  }
}
</script>

<style>

* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

h1,h2,h3,h4,h5,h6{
  color: #fff;
}
</style>
