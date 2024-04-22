<template>
  <div class="not-found">
    <div class="container">
      <h1 class="error-code">404</h1>
      <p class="error-message">Cette page introuvable.</p>
    </div>
  </div>
</template>

<style scoped>
.not-found {
  min-height: 50vh;
  display: flex;
  align-items: center;
  justify-content: center;
}

.container {
  text-align: center;
}

.error-code {
  font-size: 4rem;
}
.error-message {
  font-size: 2rem;
}
</style>