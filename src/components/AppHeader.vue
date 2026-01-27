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
  background-color:#3e2723;
  padding: 16px 0;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 20px;
  display: flex;
  align-items: center;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
  color: #f5e9dc;
}

.nav {
  margin-left: 120px;
  display: flex;
  gap: 80px;
}

.nav a {
  text-decoration: none;
  color: #f5e9dc;
  font-size: 0.95rem;
}

.nav a:hover {
  opacity: 0.8;
}

/* MOBILE */
@media (max-width: 768px) {
  .container {
    flex-direction: column;
    gap: 12px;
  }

  .nav {
    margin-left: 0;
    gap: 20px;
    flex-wrap: wrap;
    justify-content: center;
  }
} 

</style>
