<script setup lang="ts">
import { RouterView } from 'vue-router'
import Header from './Header.vue'
import Footer from './Footer.vue'
</script>

<template>
  <Header />
  <main>
    <RouterView />
  </main>
  <Footer />
</template>
