<template>
  <router-link :to="link">
    <button class="link-header">
      <i :class="remixicon"></i> {{ nomBoutton }}
    </button>
  </router-link>
</template>

<script setup>
const props = defineProps({
  nomBoutton: String,
  remixicon: String,
  link: String,
});
</script>