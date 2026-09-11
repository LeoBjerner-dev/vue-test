<script setup lang="ts">
import { ref } from 'vue'

const count = ref(0)

const increment = () => {
  count.value++
}
</script>

<template>
  <div>
    <h2>Antal: {{ count }}</h2>

    <button @click="increment">
      Öka
    </button>
  </div>
</template>