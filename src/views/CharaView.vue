<script setup>
import NavComp from '../components/Global/NavComp.vue'
import FooterComp from '../components/Global/FooterComp.vue'
</script>

<template>
  <NavComp />
  <div class="about">
    <h1>This is an about page</h1>
  </div>
  <FooterComp />
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
