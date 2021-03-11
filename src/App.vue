<template>
  <Hero />
  <PopularDestinations />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Hero from './components/Hero.vue'
import PopularDestinations from './components/PopularDestinations.vue'

export default defineComponent({
  name: 'App',
  components: { Hero, PopularDestinations }
})
</script>

<style>
body {
  @apply bg-gray-300;
}
</style>
