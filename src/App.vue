<template>
  <div id="app">
    <h1>{{ message }}</h1>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const message = ref('Welcome to Vue.js + Express!')
</script>

<style>
#app {
  font-family: Arial, sans-serif;
  text-align: center;
  margin-top: 60px;
}
</style> 