<template>
    <section class="hero">
        <div class="container">
            <h1>Mais do que café.<br/> Uma experiência.</h1>
            <p>Cafés especiais, ambiente aconchegante e uma pausa que faz sentido.</p>
            <button>Conheça nosso menu</button>           
        </div>
    </section>
</template>

<style scoped>
.hero {
  min-height: calc(100vh - 72px);
  background-color:#f5e9dc;
  display: flex;
  align-items: center;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 20px;
}

h1 {
  font-size: 3rem;
  margin-bottom: 16px;
  color: #3e2723;
}

p {
  max-width: 500px;
  font-size: 1.1rem;
  margin-bottom: 24px;
  color: #68534f;
}

button {
  padding: 12px 24px;
  background-color: #3e2723;
  color: #f5e9dc;
  border: none;
  cursor: pointer;
  font-size: 0.95rem;
}

button:hover {
  opacity: 0.9;
}
</style>