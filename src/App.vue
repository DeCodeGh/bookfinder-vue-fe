<template>
  <div id="app">
  <section class="wrapper">
    <navbar></navbar>
  </section>

   <Footer></Footer>
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
html, body {
  height: 100%;
}

#menu-toggle:checked + #menu{
  display: block;
}

#app {
  display: flex;
  flex-direction: column;
  height: 100%;
}

body{
  display:flex;
  flex-direction: column;
  height: 100vh
}

.wrapper{
  flex-grow: 1;
}

</style>
