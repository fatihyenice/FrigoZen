<template>
  <div class="stat">
    <div class="label">{{ titreCard }}</div>
    <div class="value">{{ total }}€</div>
  </div>
</template>

<script setup>
const props = defineProps({
  titreCard: String,
  total: Number,
});
</script>