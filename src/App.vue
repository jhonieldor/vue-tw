<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class='flex'>
    <img class='mx-auto' alt="Vue logo" src="./assets/logo.png" />
  </div>

   <button class="bg-red-100 px-4 py-3 hover:bg-red-300">
    Tailwind Button
  </button>
  
  <!-- <h1>Teste</h1> -->
  <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" />
</template>

<style>
#app {
  @apply text-center py-12 
}
</style>
