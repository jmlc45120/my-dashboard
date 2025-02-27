<script setup lang="ts">
import { ref } from 'vue'

// Déclaration d'une variable réactive `count`
const count = ref(0)
</script>

<template>
  <div>
    <h1>{{ count }}</h1>
    <button @click="count++">Clique moi</button>
  </div>
</template>

<style scoped>
button {
  padding: 10px;
  font-size: 16px;
  background-color: #42b883;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}
</style>
