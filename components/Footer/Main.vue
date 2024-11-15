<template>
  <footer style="background-color: #333; color: #fff; padding: 10px 20px;">
    <div
      style="max-width: 1200px; margin: 0 auto; display: flex; align-items: center; justify-content: space-between;"
    >
      <!-- Footer Brand or Copyright -->
      <div>
        <p style="margin: 0; font-size: 16px; font-weight: bold;">
          &copy; {{ currentYear }} Demo Website Footer
        </p>
      </div>

      <!-- Footer Links -->
      <div style="display: flex; gap: 15px;">
        <a href="#" style="color: #fff; text-decoration: none;">Privacy Policy</a>
        <a href="#" style="color: #fff; text-decoration: none;">Terms of Service</a>
        <a href="#" style="color: #fff; text-decoration: none;">Contact Us</a>
      </div>
    </div>
  </footer>
</template>

<script setup>
const currentYear = new Date().getFullYear();
</script>
