<script setup>
// import HomepageView from './views/HomepageView.vue'
import FavoritePlaces from './components/FavoritePlaces/FavoritePlaces.vue'
import IButton from './components/IButton/IButton.vue'
</script>

<template>
  <div class="px-6">
    <div class="text-gray mb-4">Додані маркери</div>
  </div>
  <FavoritePlaces v-for="n in 4" :key="n" />
  <IButton class="w-full mt-10">Додати маркер</IButton>
</template>
