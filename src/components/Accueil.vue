<template>
  <main class="home">
    <section class="statistique-etat">
      <div class="statistique">
        <div>
          <span class="badge good">Stable</span>
          <h1>Bienvenue 👋 — voici l’état de votre frigo</h1>
          <p class="meta">
            Suivez vos produits, anticipez les dates de péremption et gérez vos
            courses en un clin d’œil.
          </p>
        </div>

        <div class="stats" role="region" aria-label="Indicateurs clés">
          <Card titreCard="Produits au total" total="36" />
          <Card titreCard="Expirent bientôt (≤ 3 j)" total="5" />
          <Card titreCard="Budget économisé" total="24,50" />
        </div>

        <div class="actions" role="group" aria-label="Actions rapides">
          <a href="#" class="btn">➕ Ajouter un produit</a>
          <a href="#" class="btn">🧾 Générer liste</a>
          <a href="#" class="btn">⚠️ Voir alertes</a>
          <a href="#" class="btn">🍽️ Idées repas</a>
        </div>

        <div class="tips heroCard" style="padding: 12px">
          <p>
            Astuce : ajoutez une date de péremption lors de la création d’un
            produit pour activer les <strong>alertes intelligentes</strong>. 🔔
          </p>
        </div>
      </div>

      <div class="etat">
        <h2>⏳ Expirations à venir</h2>

        <div class="produits">
          <Produit
            nom="Yaourt"
            description="Lorem ipsium"
            expiration="Jour-J"
            quantity="250g"
          />
          <Produit
            nom="Yaourt"
            description="Lorem ipsium"
            expiration="Jour-J"
            quantity="250g"
          />
          <Produit
            nom="Yaourt"
            description="Lorem ipsium"
            expiration="Jour-J"
            quantity="250g"
          />
          <Produit
            nom="Yaourt"
            description="Lorem ipsium"
            expiration="Jour-J"
            quantity="250g"
          />
          <a href="#" class="btn"
            >🍽️ Supprimer les produits expirant aujourd’hui</a
          >
        </div>
      </div>
    </section>
  </main>
</template>

<script setup>
import Produit from "./card-produits/Produit.vue";
import Card from "./card-stats/Card.vue";
</script>