<template>
  <div id="app">
    <Navbar />
    <Index />
    <Footer />
  </div>
</template>

<script>
  import Navbar from './components/Navbar.vue'
  import Index from './components/Index.vue'
  import Footer from './components/Footer.vue'
  export default{
    name: 'app',
    components :{
        Navbar,
        Index,
        Footer


    }
  }
</script>

<style lang="scss" scoped>
@import './assets/css/main.css';

</style>
