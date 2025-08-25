<template>
  <button class="link-header">
    <i :class="remixicon"></i> {{ nomBoutton }}
  </button>
</template>

<script setup>
const props = defineProps({
  nomBoutton: String,
  remixicon: String,
});
</script>