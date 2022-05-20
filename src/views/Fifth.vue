<template>
  <main>
    {{a}}
  </main>
</template>

<script setup lang="ts">
const a = 1
</script>

<script lang="ts">
// Doesn't work when anything is in setup
import { defineComponent } from 'vue'

defineComponent({
  name: 'HomeView'
})
</script>
