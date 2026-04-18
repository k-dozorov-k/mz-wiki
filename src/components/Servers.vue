<template>
  <h1>ДОСТУПНЫЕ СЕРВЕРА</h1>
  <Section class="server">
    <a class="server-card evo"></a>
    <a class="server-card origin"></a>
    <a class="server-card radx"></a>
  </Section>
</template>

<style scoped>
h1 {
  color: silver;
}

.server {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  gap: 24px;
}

.server-card {
  width: 360px;
  height: 360px;
  background-color: rgba(128, 128, 128, 0.137);
  border-radius: 8px;
  border: 1px silver solid;
}
</style>
