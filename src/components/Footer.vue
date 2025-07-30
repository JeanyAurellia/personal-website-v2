<script setup>
import { Icon } from '@iconify/vue'
</script>
<template>
  <footer class="flex flex-col items-center justify-center bg-black text-white text-center py-10 gap-3">
    <h2 class="text-2xl font-bold">
      About<span class="text-yellow-400">Me.</span>
    </h2>
    <p class="text-sm text-gray-400 max-w-md mx-auto mt-2">
      There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form,
    </p>

    <div class="flex justify-center gap-4 mt-6">
      <a href="#"><Icon icon="mdi:facebook" width="24" height="24" /></a>
      <a href="#"><Icon icon="mdi:instagram" width="24" height="24" /></a>
      <a href="#"><Icon icon="mdi:twitter" width="24" height="24" /></a>
      <a href="#"><Icon icon="mdi:linkedin" width="24" height="24" /></a>
      <a href="#"><Icon icon="mdi:github" width="24" height="24" /></a>
      <a href="#"><Icon icon="mdi:youtube-tv" width="24" height="24" /></a>
    </div>
  </footer>
</template>
