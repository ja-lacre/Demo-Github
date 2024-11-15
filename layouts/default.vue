<template>
  <NavbarMain/>
  <div>
    <slot />
  </div>
  <Footermain />
</template>

<script lang="ts" setup>
  import Footermain from './components/Footer/Footermain.vue';
</script>
