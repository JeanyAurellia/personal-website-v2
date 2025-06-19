<!-- src/components/ServicePage.vue -->
<template>
  <section class="bg-[var(--background)] text-white px-10 py-16 h-full flex flex-col gap-8 justify-center">
    <div class="flex flex-col gap-2 px-10">
        <h2 class="text-3xl poppins-semibold">
        My <span class="text-yellow-400">Service</span>
        </h2>
        <p class="text-sm text-gray-400 max-w-md mt-4 ">
        There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour.
        </p>
    </div>

    <div class="grid grid-cols-1 grid-cols-3 gap-8 mt-12 px-50">
      <!-- Card 1 -->
      <div class="bg-[var(--bg-container)] py-20 px-10 rounded-lg text-center hover:shadow-lg transition flex flex-col gap-2">
        <div class="flex justify-center">
            <Icon icon="mdi:bullhorn-outline" width="40" class="mx-auto text-yellow-400" />
        </div>
        <h3 class="mt-4 font-bold text-lg">Data Analyst</h3>
        <p class="text-sm text-gray-400 mt-2">
          There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some.
        </p>
      </div>

      <!-- Card 2 -->
      <div class="bg-[var(--bg-container)] py-20 px-10 rounded-lg text-center hover:shadow-lg transition flex flex-col gap-2">
        <div class="flex justify-center">
            <Icon icon="mdi:web" width="40" class="mx-auto text-yellow-400" />
        </div>
        <h3 class="mt-4 font-bold text-lg">Web Development</h3>
        <p class="text-sm text-gray-400 mt-2">
          There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some.
        </p>
      </div>

      <!-- Card 3 -->
      <div class="bg-[var(--bg-container)] py-20 px-10 rounded-lg text-center hover:shadow-lg transition flex flex-col gap-2">
        <div class="flex justify-center">
            <Icon icon="mdi:robot-outline" width="40" class="mx-auto text-yellow-400" />
        </div>
        <h3 class="mt-4 font-bold text-lg">AI Engineer</h3>
        <p class="text-sm text-gray-400 mt-2">
          There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some.
        </p>
      </div>
    </div>
  </section>
</template>

<script setup>
import { Icon } from '@iconify/vue'
</script>
