<script setup>
import Navbar from './components/Navbar.vue'
import HomePage from './components/LandingPage.vue'
import ServicePage from './components/ServicePage.vue';
import ProjectPage from './components/ProjectPage.vue';
</script>

<template>
  <main class="overflow-hidden">
    <Navbar />

    <!-- Hero section saja yang 1 layar penuh -->
    <div id="home" class="w-screen h-screen pb-20">
        <HomePage />
    </div>
    <div id="services" class="h-screen"> 
        <ServicePage/>
    </div>
    <div id="project" class="h-screen"> 
        <ProjectPage/>
    </div>
  </main>
</template>
