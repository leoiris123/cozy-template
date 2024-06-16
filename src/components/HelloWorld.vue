<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div> 易扩展的vite+vue3+electron模版</div>

</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
