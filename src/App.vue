<script setup>
import Dropdown from './components/Dropdown.vue'
</script>

<template>
  <div>
    <img src="https://consciotech.com/img/consciotech-logo.png" class="logo" alt="Vite logo" />
  </div>
  <Dropdown msg="Welcome to ConscioTech" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
