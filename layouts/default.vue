<template>
  <NavbarMain/>
  <div class="flex">
    <SidebarMain/>
    <div class="flex-1 p-6 bg-gray-100">
      <slot />
    </div>
  </div>
  <Footermain />
</template>

<script lang="ts" setup>
  import Footermain from './components/Footer/Footermain.vue';
</script>
