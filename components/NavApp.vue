<template>
  <div class="fixed top-0 z-10 w-full bg-gray-100 bg-opacity-50 filter backdrop-filter backdrop-blur-md">
    <div class="bg-gradient-to-r from-green-500 via-blue-300 to-purple-400 h-1" />
    <div class="max-w-6xl w-full mx-auto">
      <div class="flex items-center space-x-10">
        <NuxtLink to="/" href="#" class="text-xl font-bold tracking-tighter">
          <span class="text-green-500">t</span>eam<span class="text-green-500">C</span>oding
        </NuxtLink>
        <!-- <a href="#" class="text-base py-4 hover:text-green-600 transition-all ease-in-out">Home</a> -->
        <a href="#" class="text-base py-4 hover:text-green-600 transition-all ease-in-out">Artikel</a>
        <a href="#" class="text-base py-4 hover:text-green-600 transition-all ease-in-out">Archive</a>
        <div class="flex-1 flex justify-end items-center">
          <form action="">
            <input class=" outline-none py-1 px-4 bg-transparent focus:bg-white text-gray-500 transition-all ease-in-out" type="text" placeholder="Search...">
          </form>
        </div>
      </div>
    </div>
  </div>
</template>
