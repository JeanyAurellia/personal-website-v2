<script setup>
import Navbar from './components/Navbar.vue'
import HomePage from './components/LandingPage.vue'
import ServicePage from './components/ServicePage.vue';
import ProjectPage from './components/ProjectPage.vue';
import ContactMe from './components/ContactMe.vue';
import Footer from './components/Footer.vue';
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
    <div id="project" class="h-full"> 
        <ProjectPage/>
    </div>
    <div id="contact" class="h-screen"> 
        <ContactMe/>
    </div>
    <Footer/>
  </main>
</template>
