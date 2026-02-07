<script setup>
import { ref } from 'vue'

const isMenuOpen = ref(false)
</script>

<template>
  <header class="sticky top-0 z-50 bg-white/90 dark:bg-background-dark/90 backdrop-blur-md border-b border-gray-100 dark:border-gray-800">
    <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
      <div class="flex items-center gap-3">
        <img src="/public/logo.png" alt="VitaRecord" class="h-16 w-auto" />
      </div>
      <nav class="hidden md:flex items-center gap-8">
        <a class="text-sm font-bold text-gray-700 dark:text-gray-200 hover:text-primary transition-colors" href="#">Inicio</a>
        <a class="text-sm font-bold text-gray-700 dark:text-gray-200 hover:text-primary transition-colors" href="#">Servicios</a>
        <a class="text-sm font-bold text-gray-700 dark:text-gray-200 hover:text-primary transition-colors" href="#">Especialistas</a>
        <a class="text-sm font-bold text-gray-700 dark:text-gray-200 hover:text-primary transition-colors" href="#">Seguros</a>
      </nav>
      <div class="flex items-center gap-4">
        <!-- Mobile Menu Button -->
        <button @click="isMenuOpen = !isMenuOpen" class="md:hidden flex items-center justify-center size-10 rounded-full hover:bg-gray-100 dark:hover:bg-gray-800 transition-colors">
          <span class="material-symbols-outlined">{{ isMenuOpen ? 'close' : 'menu' }}</span>
        </button>

        <button class="flex items-center justify-center size-10 rounded-full hover:bg-gray-100 dark:hover:bg-gray-800 transition-colors">
          <span class="material-symbols-outlined">search</span>
        </button>
        <button class="hidden md:block bg-primary text-white px-6 py-2.5 rounded-full font-bold text-sm shadow-lg shadow-primary/20 hover:bg-blue-700 transition-all">
          Portal Paciente
        </button>
      </div>
    </div>
    
    <!-- Mobile Menu -->
    <div v-show="isMenuOpen" class="md:hidden border-t border-gray-100 dark:border-gray-800 bg-white dark:bg-background-dark absolute w-full left-0 shadow-lg">
      <nav class="flex flex-col p-6 gap-4">
        <a class="text-sm font-bold text-gray-700 dark:text-gray-200 hover:text-primary transition-colors" href="#">Inicio</a>
        <a class="text-sm font-bold text-gray-700 dark:text-gray-200 hover:text-primary transition-colors" href="#">Servicios</a>
        <a class="text-sm font-bold text-gray-700 dark:text-gray-200 hover:text-primary transition-colors" href="#">Especialistas</a>
        <a class="text-sm font-bold text-gray-700 dark:text-gray-200 hover:text-primary transition-colors" href="#">Seguros</a>
        <button class="bg-primary text-white w-full py-3 rounded-xl font-bold text-sm shadow-lg shadow-primary/20 hover:bg-blue-700 transition-all mt-2">
          Portal Paciente
        </button>
      </nav>
    </div>
  </header>
</template>
