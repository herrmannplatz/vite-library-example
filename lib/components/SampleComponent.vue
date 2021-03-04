<template>
  <h1>{{ whoop }}</h1>
</template>

<script lang="ts">
import { ref, defineComponent } from 'vue'
export default defineComponent({
  name: 'SampleComponent',
  setup: () => {
    const whoop = ref('🎉 whoop 🎉')
    return { whoop }
  }
})
</script>
