<script setup>
import { ref } from 'vue'

const key = ref("chicago");
</script>

<template>
  <p>meow</p>
  <main>
    <img :src="`${baseDir}images/${fixtures[key].img}`">
    <h1>Filename: {{ fixtures[key].img }}</h1>
  </main>
</template>
