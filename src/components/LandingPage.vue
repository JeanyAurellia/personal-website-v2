<script setup>
import bgImage from '../assets/pict/background.jpeg'
import { Icon } from '@iconify/vue'
</script>

<template>
  <div class="flex w-full h-full overflow-hidden">
  <!-- Kiri -->
    <div class="w-1/2 bg-[var(--background)] flex flex-col justify-center px-20 py-16">
      <!-- Tulisan + Button di tengah -->
      <div class="flex flex-col items-start gap-3">
        <div class="text-7xl playfair-display-500 text-white">
          Hello! <br />
          I’m Jeany Aurellia
        </div>
        <p class="w-96 text-white mt-4">
          I’m a freelance web developer based in Indonesia who loves to craft attractive design experiences for the web.
        </p>

        <!-- Tombol tepat di bawah teks -->
        <div class="mt-4 flex gap-4">
          <button class="bg-indigo-500 text-white px-4 py-2 rounded-md text-sm">📧 Email me</button>
          <a
            href="#"
            class="text-white text-sm px-4 py-2 rounded-md border border-white hover:bg-white hover:text-black transition"
          >
            ⬇️ Download CV
          </a>
        </div>
      </div>
    </div>


    <!-- Kanan -->
    <div class="w-1/2 bg-cover bg-center" :style="{ backgroundImage: `url(${bgImage})` }"></div>
  </div>

  <!-- Bagian ikon -->
  <div class="bg-black py-5  px-10">
    <div class="flex justify-center gap-10">
      <Icon icon="devicon-plain:figma" width="50" height="50" />
      <Icon icon="devicon-plain:html5" width="50" height="50" />
      <Icon icon="devicon-plain:css3" width="50" height="50" />
      <Icon icon="devicon-plain:vuejs" width="50" height="50" />
      <Icon icon="devicon-plain:nuxt-wordmark" width="50" height="50" />
      <Icon icon="devicon-plain:googlecolab" width="50" height="50" />
      <Icon icon="devicon-plain:python" width="50" height="50" />
    </div>
  </div>
</template>
