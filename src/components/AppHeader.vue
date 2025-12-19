<template>
  <header class="header">
    <div class="container">
      <div class="logo">Coffee House</div>

      <nav class="nav">
        <a href="#">Início</a>
        <a href="#">Sobre</a>
        <a href="#">Menu</a>
        <a href="#">Contato</a>
      </nav>
    </div>
  </header>
</template>

<style scoped>
.header {
  width: 100%;
  background-color: #1f1f1f;
  padding: 16px 0;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 20px;

  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.3rem;
  font-weight: bold;
  color: #f5f5f5;
}

.nav a {
  margin-left: 20px;
  text-decoration: none;
  color: #f5f5f5;
  font-size: 0.95rem;
}

.nav a:hover {
  opacity: 0.8;
}
</style>
