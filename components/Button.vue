<template>
  <button
    class="text-lg bg-almost-black text-almost-white block px-7 py-3 rounded-2xl hover:bg-almost-white hover:text-almost-black"
    :class="{ 'm-auto': centered }"
  >
    <slot />
  </button>
</template>
<script setup lang="ts">
  // Define props
  interface Props {
    centered: boolean;
  }

  // Initialize props with default values (https://vuejs.org/guide/typescript/composition-api.html#typing-component-props)
  const { centered = false } = defineProps<Props>();
</script>
