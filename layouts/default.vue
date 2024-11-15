<template>
  <NavbarMain/>
  <div class="flex">
    <SidebarMain/>
    <div class="flex-1 p-6 bg-gray-100">
      <slot />
    </div>
  </div>
</template>

<script lang="ts" setup></script>
