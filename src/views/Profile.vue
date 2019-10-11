<template>
  <div class="profile p-4">
    <section class="mx-auto flex w-full mb-4">
      <ul class="flex  w-full justify-center">
          <li  class="px-1"> Profile </li>
          <li class="px-1"> Preferences </li>
           <li class="px-1"> Social</li>
           <li class="px-1">Books</li>
      </ul>
    </section>

    <section class="flex  justify-center">
          <form action="" class="w-full max-w-lg  flex flex-wrap p-4 border border-gray-400">
            <section class="w-full md:w-1/2 px-3  mb-6 md:mb-6">
                <label for="" class="block mb-1 font-semibold">Display name</label>
                <input type="text" name="" class="block appearance-none border rounded border-indigo-700 p-2" id="" placeholder="display name">
            </section>

            <section class="w-full md:w-1/2  px-3  mb-6 md:mb-6">
                <label for=" " class="block font-semibold mb-1">Location</label>
                <input type="text" name=" " placeholder="e.g accra" class="border p-2 rounded border-indigo-700" id="">
            </section>

            <section class="w-full md:w-1/2 px-3  mb-6 md:mb-6">
                <label for="" class="block mb-1 font-semibold">Username</label>
                <input type="text" name="" class="block appearance-none border rounded border-indigo-700 p-2" id="" placeholder="username">
            </section>

            <section class="w-full md:w-1/2  px-3  mb-6 md:mb-6">
                <label for=" " class="block font-semibold mb-1">Email Address</label>
                <input type="text" name=" "  class="border p-2 rounded border-indigo-700" placeholder="email@example.com" id="">
            </section>

            <section class="w-full px-3">
                <button class="bg-indigo-700 text-white tracking-tight leading-relaxed p-2 rounded border-b-4 border-indigo-400 hover:border-indigo-600 font-bold hover:bg-indigo-500"> Save</button>
            </section>

          </form>
    </section>
  </div>
</template>

<script>
export default{

}
</script>

<style>


</style>