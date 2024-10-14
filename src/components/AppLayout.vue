<script setup>
import Navbar from "./Navbar.vue";
import Footer from "./Footer.vue";
</script>

<template>
  <div class="layout-container">
    <div class="container">
      <Navbar />
    </div>
    <div class="layout-content">
      <slot></slot>
    </div>
    <Footer />
  </div>
</template>

<style></style>
