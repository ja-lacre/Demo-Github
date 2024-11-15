<template>
    <div class="flex">
      <div id="sidebar" class="w-64 text-white min-h-screen">
        <div class="p-4">
          <h1 class="text-2xl font-semibold">Sidebar</h1>
        </div>
        <ul>
          <li class="hover:bg-gray-700">
            <NuxtLink to="/" class="block p-4">Home</NuxtLink>
          </li>
          <li class="hover:bg-gray-700">
            <NuxtLink to="/about" class="block p-4">About</NuxtLink>
          </li>
          <li class="hover:bg-gray-700">
            <NuxtLink to="/services" class="block p-4">Services</NuxtLink>
          </li>
          <li class="hover:bg-gray-700">
            <NuxtLink to="/contact" class="block p-4">Contact</NuxtLink>
          </li>
        </ul>
      </div>
  
      <div class="flex-1 p-6 bg-gray-100">
        <Nuxt />
      </div>
    </div>
  </template>
  
<script>
  export default {
    name: 'default-layout'
  }
</script>
  
<style scoped>
    #sidebar {
        background-color: #333;
    }
</style>