<script setup lang="ts">
defineProps(['src', 'url', 'alt'])
</script>

<template>
  <a v-bind:href="url" target="_blank" rel="noreferrer" v-bind:alt="alt">
    <img v-bind:src="src" />
  </a>
</template>
