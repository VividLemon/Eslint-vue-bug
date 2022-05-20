<template>
  <main>
    {{a}}
  </main>
</template>

<script setup lang="ts">
// defineComponent is never read, but error is gone. Not sure how this would behave in build
import { ref, defineComponent } from 'vue'

const a = ref(1)

</script>

<script lang="ts">

export default defineComponent({
  name: 'HomeView'
})
</script>
