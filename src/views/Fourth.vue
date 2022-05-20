<template>
  <main>
    {{a}}
  </main>
</template>

<script setup lang="ts">

</script>

<script lang="ts">
// Works fine when nothing is inside script setup
import { defineComponent } from 'vue'

defineComponent({
  name: 'HomeView'
})
</script>
