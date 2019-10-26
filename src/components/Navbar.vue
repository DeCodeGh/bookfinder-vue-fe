<template>
  <div class="navbar">
    <nav class="flex items-center justify-between flex-wrap bg-teal-500 p-6">
      <section class="flex items-center flex-shrink-0 text-white mr-6">
        <span class="text-xl font-bold ">BookFind App</span>
      </section>



          <label for="menu-toggle" class="cursor-pointer lg:hidden block">

          <svg class="fill-current h-3 w-3" viewBox="0 0 25 25" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
          </label>
          <input type="checkbox" name="" class="hidden" id="menu-toggle">



      <section class="w-full hidden block flex-grow lg:flex lg:items-center lg:w-auto" id="menu">
        <section class="text-sm lg:flex-grow">
          <router-link to="/" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">Home</router-link>
          <a href="" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">New Books</a>
          <a href="" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">Review</a>
          <router-link to="/contact" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">Contact</router-link>
        </section>
        <section>
        <router-link  to="/login" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">Login</router-link>
        <router-link to="/register" class="inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-teal-500 hover:bg-white mt-4 lg:mt-0">Sign Up</router-link>
        </section>
      </section>

    </nav>
      <router-view></router-view>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>