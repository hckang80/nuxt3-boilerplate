<script setup lang="ts">
useMeta({
  title: 'Nuxt3 Boilerplate',
  htmlAttrs: {
    lang: 'en',
  },
})

</script>

<template>
  <div>
    Some shared layout content:
    <slot />
  </div>
</template>
