<template>
  <input type="search" class="search" placeholder="Поиск информации на сайте..."></input>
</template>

<script setup></script>

<style scoped>
.search {
  width: 650px;
  height: 50px;
  border: 1px grey solid;
  border-radius: 12px;
  background: transparent;
}

.search::placeholder {
  color: silver;
}
</style>
