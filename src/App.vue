<template>
  <Header />
  <main class="min-h-screen">
    <router-view></router-view>
  </main>
  <Footer />
</template>

<script setup>
import { RouterView } from "vue-router";
import Header from "./components/Header.vue"
import Footer from "./components/Footer.vue"
</script>

<style lang="scss"></style>