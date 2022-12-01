<script setup>
import Header from "../components/Header.vue"
import Hero from "../components/Hero.vue"
import Footer from "../components/Footer.vue"
</script>

<template>
 <div class="app-container">
      <Header />
      <Hero />
      <Footer />
  </div>
</template>

<style scoped>
.app-container {
  background-color: black;
  display: grid;
  grid-template-rows: 1fr 1fr 1fr;
  width: 100vw;
  height: 100vh;
}

</style>
