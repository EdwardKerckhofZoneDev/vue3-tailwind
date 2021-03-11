<template>
  <div id="app" class="min-h-screen bg-gray-100">
    <landing />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Landing from './components/Landing.vue'

export default defineComponent({
  name: 'App',
  components: { Landing }
})
</script>

<style></style>
