<template>
  <img
    class="rounded-lg shadow-xl mb-6 sm:mb-8 sm:h-64 sm:w-full sm:object-cover object-center lg:hidden"
    src="../assets/img/beach-work.jpg"
    alt="Woman working on the beach"
  />
  <h1
    class="text-2xl font-bold text-gray-800 mb-2 sm:text-4xl sm:mb-4 lg:text-3xl xl:text-4xl"
  >
    You can work from anywhere.
    <p class="text-indigo-500">Take advantage of it.</p>
  </h1>
  <p class="text-gray-600 mb-4 sm:text-xl sm:mb-6">
    Workcation helps you find work-friendly rentals in beautiful locations so
    you can enjoy some nice weather even when you're not on vacation.
  </p>
  <a
    class="inline-block px-5 py-3 rounded-lg shadow-lg bg-indigo-500 text-white uppercase tracking-wider font-semibold text-sm sm:text-base"
    href="#"
  >
    Book your escape
  </a>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Landing'
})
</script>

<style></style>
