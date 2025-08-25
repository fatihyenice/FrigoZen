<template>
  <header class="header-glass">
    <div class="logo">FrigoZen</div>
    <!-- <div class="budget-info">
      <div class="budget-item">
        <span>Budget Mensuel</span>
        <strong> 150€</strong>
      </div>
      <div class="budget-item">
        <span>Dépensé</span>
        <strong> 85€</strong>
      </div>
      <div class="budget-item">
        <span>Panier</span>
        <strong> 30€</strong>
      </div>
    </div> -->
    <div class="header-actions">
      <Boutton nomBoutton="Accueil" remixicon="ri-home-2-line" />
      <Boutton
        nomBoutton="Liste de mes courses"
        remixicon="ri-file-list-3-line"
      />
      <Boutton nomBoutton="Inventaire" remixicon="ri-cloudy-line" />
      <Boutton nomBoutton="Liste de courses" remixicon="ri-home-2-line" />
    </div>
  </header>
</template>

<script setup>
import Boutton from "../boutton-header/boutton.vue";
</script>