<template>
  <header class="sticky top-0 w-full h-auto bg-gradient-to-r from-teal-900 font-Roboto shadow-md">
    <nav class="container px-6 py-8 mx-auto md:flex md:justify-between md:items-center">
      <div class="flex items-center justify-between">
        <RouterLink to="/">
          <p class="text-3xl font-bold italic flex items-center md:text-2xl">
            Zikrullah Danish
          </p>
        </RouterLink>
        <!-- Mobile menu button -->
        <div @click="toggleNav" class="flex items-center md:hidden cursor-pointer">
          <i class="fa-solid fa-bars text-2xl"></i>
        </div>
      </div>

      <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
      <ul
        :class="showMenu ? 'flex' : 'hidden'"
        class="flex-col mt-8 space-y-4 md:flex md:space-y-0 md:flex-row md:items-center md:space-x-10 md:mt-0"
      >
        <RouterLink to="#home">
          <li class="border-b border-b-teal-900 hover:text-gray-600">Home</li>
        </RouterLink>
        <RouterLink to="#about">
          <li class=" hover:text-gray-600">About</li>
        </RouterLink>
        <RouterLink to="#resume">
          <li class=" hover:text-gray-600">Resume</li>
        </RouterLink>
        <RouterLink to="#services">
          <li class=" hover:text-gray-600">Services</li>
        </RouterLink>
        <RouterLink to="#contact">
          <li class=" hover:text-gray-600">Contanct</li>
        </RouterLink>
      </ul>
    </nav>
  </header>
</template>

<script setup>
import { RouterLink } from "vue-router";
import { ref } from "vue";
const showMenu = ref(false);
const toggleNav = () => {
  showMenu.value = !showMenu.value;
};
</script>
