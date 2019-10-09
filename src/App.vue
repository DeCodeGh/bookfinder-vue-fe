<template>
  <div id="app">
    <Navbar />
    <Footer />
  </div>
</template>

<script>
  import Navbar from './components/Navbar.vue'
  import Footer from './components/Footer.vue'
  export default{
    name: 'app',
    components :{
        Navbar,
        Footer
    }
  }
</script>

<style lang="scss" scoped>
@import './assets/css/main.css';


</style>
