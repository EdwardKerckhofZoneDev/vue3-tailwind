<template>
  <div
    className="max-w-md sm:max-w-xl lg:max-w-full mx-auto px-8 lg:px-40 py-10"
  >
    <h2 className="text-xl text-gray-900">Popular destinations</h2>
    <p className="mt-2 text-gray-600">
      A selection of great work-friendly cities with lots to see and explore.
    </p>
    <div className="mt-6 grid gap-6 lg:grid-cols-2 xl:grid-cols-3">
      <DestinationCard
        v-for="(destination, index) in destinations"
        :key="index"
        :destination="destination"
      ></DestinationCard>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import popularDestinations from '../data/popularDestinations'
import DestinationCard from './destinations/DestinationCard.vue'

export default defineComponent({
  name: 'PopularDestinations',
  components: { DestinationCard },
  data: () => ({
    destinations: popularDestinations
  })
})
</script>
