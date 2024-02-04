<script setup lang="ts">
import Header from './Header.vue';
import Footer from './Footer.vue';
import Content from './Content.vue';
</script>

<template>
  <div class="main-container">
    <Header />
    <Content />
    <Footer />
  </div>
</template>

<style>
.main-container {
  margin-left: 20%;
  margin-right: 20%;
}
</style>
