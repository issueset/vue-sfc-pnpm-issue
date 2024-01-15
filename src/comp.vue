<script setup lang="ts">
import type { VueNodeViewProps } from 'prosekit/vue'

const props = defineProps<VueNodeViewProps>()
</script>

<template>
  <pre>{{ props.node }}</pre>
</template>
