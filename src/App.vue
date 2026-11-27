<script setup>
import TheNavbar from './components/common/TheNavbar.vue'
import TheFooter from './components/common/TheFooter.vue'
</script>

<template>
  <TheNavbar />
  <main>
    <RouterView />
  </main>
  <TheFooter />
</template>