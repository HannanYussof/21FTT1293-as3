<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <body class="bg-red-100">
    <div class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-2xl">

        <div class="md:flex">
          <div class="md:shrink-0">
            <img class="h-48 w-full object-cover md:h-full md:w-48" src="ITME.jpg">
          </div>
          
          <div class="p-8">
            <div class="uppercase tracking-wide text-sm font-semibold">Hannan Yussof</div>
            <div class="block mt-1 text-lg leading-tight font-medium text-black">21FTT1293</div>
            
            <p class="mt-2 text-slate-500">Assignment 3 of module Web Application and Development Tools - WD4308</p>
          </div>

        </div>
      </div>
  </body>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
