<script setup>

</script>

<template>
  <div>
    <RouterLink active-class="active" to="/">Home</RouterLink>
    <RouterLink active-class="active" to="/about">About</RouterLink>
  </div>
</template>

<style scoped>
.active {
  font-weight: bold;
  color: rgb(227, 150, 49);
}

</style>