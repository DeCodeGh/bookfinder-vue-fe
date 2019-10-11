<template>

  <div class="home">
      <section class="sm:flex xs:flex-wrap p-4">
        <!-- sidebar -->
        <section class="w-1/4  p-4 ">
          <section class="mb-4  w-full">
          <h3 class="text-indigo-700 text-2xl font-bold ">Categories</h3>
          <ul class="hidden md:block list-disc px-8 w-100 ">
              <li class="">Teen & Young</li>
              <li>C</li>
              <li>Business & Money</li>
              <li>Teen & Young</li>
              <li>Teen & Young</li>
              <li>Biographies & Memoirs</li>
              <li>Business & Money</li>
              <li>Teen & Young</li>
          </ul>

          <select name="" id="" class="md:hidden  w-100">
            <option value=" " class="" selected> Lorem ipsum.</option>
            <option value=" ">2</option>
            <option value=" ">3</option>
            <option value=" ">4</option>
            <option value=" ">5</option>
          </select>
          </section>
          <section class="mb-4 w-full">
            <h3 class="text-indigo-700 text-2xl font-bold ">Authors</h3>
          <ul class="hidden md:block list-disc px-8">
              <li>Teen  Young</li>
              <li>Biographies  Memoirs</li>
              <li>Business  Money</li>
              <li>Teen  Young</li>
              <li>Teen  Young</li>
              <li>Biographies  Memoirs</li>
              <li>Business  Money</li>
              <li>Teen  Young</li>
          </ul>

          <select name="" id="" class="md:hidden w-100">
            <option value=" " selected> Lorem ipsum.</option>
            <option value=" ">2</option>
            <option value=" ">3</option>
            <option value=" ">4</option>
            <option value=" ">5</option>
          </select>

          </section>
        </section>
        <!-- /sidebar -->

        <section class="md:w-3/4 w-full    flex flex-wrap mx-2 mb-8">
          <section class="w-full flex mb-4 -mx-2">
            <form action="" class="flex flex-wrap px-2 w-full">
              <input type="text" class="w-3/4 border appearance-none py-3 px-4 leading-light focus:outline-none focus:bg-white rounded p-2 border-gray-500 bg-gray-200" placeholder="Search for books" name="" id="">
              <button class="w-1/4 bg-indigo-700 text-white font-bold -mx-px-1">Search</button>
            </form>
          </section>
          <section class="px-2 max-w-md  flex  sm:w-screen  md:w-1/2 lg:w-1/3 mb-3">
            <section class="border border-gray-400">
            <img src="https://images.unsplash.com/photo-1544947950-fa07a98d237f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=634&q=80" class="object-cover h-48 w-full" alt="">
          <section class="p-2">
              <section class="font-bold"><router-link to="/book">Book 2</router-link></section>
              <section class="font-semibold text-gray-600"> My favorite Author</section>
              <section class="flex ">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg>
              </section>
          </section>
          </section>
        </section>
        <!--  -->
        <section class="px-2 max-w-md  flex  w-full  md:w-1/2 lg:w-1/3 mb-3">
            <section class="border border-gray-400">
             <img src="https://images.unsplash.com/photo-1544947950-fa07a98d237f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=634&q=80" class="object-cover h-48 w-full" alt="">
          <section class="p-2">
              <section class="font-bold"><router-link to="/book">Book 2</router-link></section>
              <section class="font-semibold text-gray-600">My favorite Author</section>
                <section class="flex ">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg>
              </section>

          </section>
          </section>
        </section>
        <!--  -->

         <section class="px-2 max-w-md  flex  w-full  md:w-1/2 lg:w-1/3 mb-3">
            <section class="border border-gray-400">
             <img src="https://images.unsplash.com/photo-1544947950-fa07a98d237f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=634&q=80" class="object-cover h-48 w-full" alt="">
          <section class="p-2">
              <section class="font-bold"><router-link to="/book">Book 2</router-link></section>
              <section class="font-semibold text-gray-600">My favorite Author</section>
                <section class="flex ">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg>
              </section>
          </section>
          </section>
        </section>
        <!--  -->

         <section class="px-2 max-w-md  flex  w-full  md:w-1/2 lg:w-1/3 mb-3">
            <section class="border border-gray-400">
             <img src="https://images.unsplash.com/photo-1544947950-fa07a98d237f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=634&q=80" class="object-cover h-48 w-full" alt="">
          <section class="p-2">
              <section class="font-bold"><router-link to="/book">Book 2</router-link></section>
              <section class="font-semibold text-gray-600">My favorite Author</section>
                <section class="flex ">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg>
              </section>

          </section>
          </section>
        </section>
        <!--  -->

         <section class="px-2 max-w-md  flex  w-full  md:w-1/2 lg:w-1/3 mb-3">
            <section class="border border-gray-400">
             <img src="https://images.unsplash.com/photo-1544947950-fa07a98d237f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=634&q=80" class="object-cover h-48 w-full" alt="">
          <section class="p-2">
              <section class="font-bold"><router-link to="/book">Book 2</router-link></section>
              <section class="font-semibold text-gray-600">My favorite Author</section>
                <section class="flex ">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg>
              </section>

          </section>
          </section>
        </section>
        <!--  -->
      </section>
    </section>
  </div>
</template>

<script>
  export default{

  }
</script>

<style lang="scss" >

</style>
