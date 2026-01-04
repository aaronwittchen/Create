<script setup>
import { Icon } from '@iconify/vue';
</script>

<template>
  <footer class="py-6 text-center text-sm opacity-60 border-t border-white/15 -mx-8 px-8">
    <span class="inline-flex items-center gap-1 flex-wrap justify-center">
      Made with
      <Icon icon="simple-icons:astro" class="inline text-[#FF5D01]" /> Astro,
      <Icon icon="simple-icons:vuedotjs" class="inline text-[#4FC08D]" /> Vue, and
      <Icon icon="simple-icons:bun" class="inline text-[#FBF0DF]" /> Bun!
    </span>
  </footer>
</template>