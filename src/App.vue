<script setup>
import Navbar from './components/Navbar.vue';
import HomeSection from './components/HomeSection.vue';
import SoftSkilsSection from './components/SoftSkilsSection.vue'
import ProjectsSection from './components/ProjectsSection.vue'
import FlowSection from './components/FlowSection.vue'
import ContactSection from './components/ContactSection.vue';
import FooterSection from './components/FooterSection.vue';
</script>

<template>
  <div>
    <Navbar />
    <div class="">
    <HomeSection/>
    <SoftSkilsSection/>
    <FlowSection/>
    <ProjectsSection/>
    <ContactSection/>
    <FooterSection/>      
    </div>

  </div>
</template>