<script setup>
import Nav from "@/components/Nav.vue";
import {ref} from "vue";
const randomState = ref("")
</script>

<template>
  <div>
    <Nav />
    <RouterView />
  </div>
</template>