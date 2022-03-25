<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
<img class="w-10 h-10 rounded-full" src="./assets/logo.png" alt="Rounded avatar">
<img class="w-10 h-10 rounded" src="./assets/logo.png" alt="Default avatar">
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
