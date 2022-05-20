<!-- filename: TodoItem.vue -->
<!-- Does not change anything -->
<template>
  <div class="about">
    {{a}}
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'
const a = ref(1)
</script>
