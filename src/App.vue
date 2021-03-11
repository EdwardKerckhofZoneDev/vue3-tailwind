<template>
  <div id="app" class="min-h-screen bg-gray-100">
    <div class="px-8 py-12">
      <Logo class="h-10 mb-6" />
      <Landing />
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

<style></style>
