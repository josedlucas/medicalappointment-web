<script setup>
import NavBar from './components/NavBar.vue'
import HeroSection from './components/HeroSection.vue'
import ServicesSection from './components/ServicesSection.vue'
import PatientSection from './components/PatientSection.vue'
import ClinicSection from './components/ClinicSection.vue'
import FooterSection from './components/FooterSection.vue'
import CallToAction from './components/CallToAction.vue'
</script>

<template>
  <NavBar />
  <main>
    <HeroSection />
    <ServicesSection />
    <PatientSection />
    <ClinicSection />
    <CallToAction />
  </main>
  <FooterSection />
</template>

<style scoped>
</style>
