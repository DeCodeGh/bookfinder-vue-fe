<template>
  <div class="login">
    <section class="w-full p-6 mt-4 ">
      <h4 class="text-center text-2xl mb-4 font-semibold text-indigo-700">Login</h4>
      <form action="" class="w-full border border-gray-300 p-5 rounded mx-auto  max-w-md justify-center items-center">
      <section class="flex flex-wrap -mx-3 mb-6">
        <section class="w-full md:w-full px-3 mb-4 md:mb-0">
          <label for="" class="block uppercase tracking-wide text-gray-700 text-xs mb-4 font-bold text-lg">Email</label>
          <input type="text" class="appearance-none block w-full bg-gray-200 text-gray-700 border border-indigo-500 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white" name="" id="" placeholder="">
        </section>

        <section class="w-full md:w-full px-3 mb-4 md:mb-0">
          <label for="" class="block uppercase tracking-wide text-gray-700 text-xs mb-4 font-bold text-lg">Password</label>
          <input type="password" class="appearance-none block w-full bg-gray-200 text-gray-700 border border-indigo-500 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white" name="" id="" placeholder="">
        </section>

        <section class="w-full md:w-full px-3 mb-4 md:mb-0">
          <button class="border-indigo-500 bg-indigo-700 border-b-4 py-2 px-4 rounded hover:bg-indigo-400 hover:border-indigo-500 text-white">
            Login
          </button>
        </section>
      </section>
      </form>

    </section>
  </div>
</template>
<script>
  export default{
name: 'login'
  }
</script>
<style>

</style>