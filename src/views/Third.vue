<template>
  <main>
    {{a}}
  </main>
</template>

<script setup lang="ts">
// defineComponent is never read
import { ref, defineComponent } from 'vue'

const a = ref(1)

</script>

<script lang="ts">

export default defineComponent({
  name: 'HomeView'
})
</script>
