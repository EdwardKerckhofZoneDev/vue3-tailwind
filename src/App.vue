<template>
  <div class="bg-gray-100 lg:grid lg:grid-cols-2 2xl:grid-cols-5">
    <div
      class="px-8 py-12 max-w-md mx-auto sm:max-w-xl lg:px-12 lg:py-24 lg:max-w-full xl:mr-0 xl:max-w-xl 2xl:col-span-2"
    >
      <Logo class="h-10 mb-6 sm:mb-8" />
      <Landing />
    </div>
    <div class="hidden relative lg:block 2xl:col-span-3">
      <img
        class="absolute inset-0 w-full h-full object-cover object-center"
        src="./assets/img/beach-work.jpg"
        alt="Woman working on the beach"
      />
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Landing from './components/Landing.vue'
import Logo from './components/shared/Logo.vue'

export default defineComponent({
  name: 'App',
  components: { Landing, Logo }
})
</script>

<style>
body {
  @apply bg-gray-100;
}
</style>
