<template>
  <main>
    {{a}}
  </main>
</template>

<script setup lang="ts">
import { ref } from 'vue'
const a = ref(1)
</script>

<script lang="ts">
// Breaks everything
import { defineComponent } from 'vue'

defineComponent({
  name: 'HomeView'
})
</script>