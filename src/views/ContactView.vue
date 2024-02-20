<script setup>
import {useRoute} from "vue-router";
import cars from "../data/cars.json"

const route = useRoute()
const car = cars.find(c => c.id === parseInt(route.params.id))

</script>

<template>
  <div>
    <h1>
      Contact Info
    </h1>
    {{ car.contact.dealer }}
    {{ car.contact.number }}
  </div>
</template>

<style scoped>

</style>