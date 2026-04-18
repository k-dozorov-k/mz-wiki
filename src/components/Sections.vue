<template>
  <section class="main">
    <h1>Разделы</h1>
    <section class="table">
      <a class="table-card table-card-big">
        <div class="table-card-content">
          <div class="table-card-content-top"><h3>Правила</h3></div>
          <p>Правила сервера</p>
        </div>
      </a>
      <a class="table-card">
        <div class="table-card-content">
          <div class="table-card-content-top"><h3>Крафты</h3></div>
          <p>Все крафты и их подсчет</p>
        </div>
      </a>
      <a class="table-card">
        <div class="table-card-content">
          <div class="table-card-content-top"><h3>Улучшения</h3></div>
          <p>Улучшения и их подсчет</p>
        </div>
      </a>
    </section>
  </section>
</template>

<style scoped>
.main {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
}

h1 {
  color: silver;
}

.table {
  max-width: 1134px;
  width: 100%;
  display: grid;
  grid-template-columns: minmax(0, 1fr) minmax(0, 1fr);
  grid-gap: 18px;
}

.table-card {
  grid-column: 1 / -1;
  border: 1px silver solid;
  border-radius: 18px;
  cursor: pointer;
}

.table-card-big {
  grid-column: 1 / -1;
}

.table-card-content {
  padding: 10px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: space-between;

  h3 {
    color: silver;
  }

  p {
    color: rgba(192, 192, 192, 0.5);
  }
}
</style>
