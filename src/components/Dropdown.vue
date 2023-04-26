<script setup>
import { ref } from 'vue';

defineProps({
  msg: String,
});
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="dropdown">Complete your code here</div>

  <p>
    Check out
    <a href="https://vuejs.org/guide/essentials/reactivity-fundamentals.html" target="_blank"
      >Documentation</a
    >
    for hlp.
  </p>
</template>

<style scoped>
/* enter your styles here */
</style>
