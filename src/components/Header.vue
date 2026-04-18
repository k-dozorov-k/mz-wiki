<template>
  <header>
    <a href="/mz-wiki/src/App.vue">Logo</a>
    <Search />
    <div>server-info</div>
  </header>
</template>

<script setup>
import Search from './Search.vue'
</script>

<style scoped>
header {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
}
</style>
