<template>
  <div class="produit">
    <div>
      <strong>{{ nom }}</strong>
      <p>
        {{ description }} • <span class="quantity-produit">{{ quantity }}</span>
      </p>
    </div>

    <div>
      <div class="badge danger">{{ expiration }}</div>
    </div>
  </div>
</template>

<script setup>
const props = defineProps({
  nom: String,
  description: String,
  expiration: String,
  quantity: String,
});
</script>