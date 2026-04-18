<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import Servers from './components/Servers.vue'
import Sections from './components/Sections.vue'
</script>

<template>
  <div id="app">
    <Header />
    <div id="main">
      <Hero />
      <Servers />
      <Sections />
    </div>
  </div>
</template>

<script setup></script>

<style scoped></style>
