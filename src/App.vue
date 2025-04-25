<template>
  <div id="app">
    <header>
      <nav>
        <RouterLink to="/">Home</RouterLink> |
        <RouterLink to="/about">About</RouterLink> |
        <RouterLink to="/projects">Projects</RouterLink> |
        <RouterLink to="/contact">Contact</RouterLink>
      </nav>
    </header>

    <main>
      <RouterView />
    </main>

    <footer>
      <p>&copy; 2025 Your Name</p>
    </footer>
  </div>
</template>

<script setup>
// you can import any global composables or use CSS here
</script>

<style scoped>
header {
  padding: 1rem;
  background-color: #333;
  color: white;
}

nav a {
  margin: 0 1rem;
  text-decoration: none;
  color: #fff;
}

main {
  padding: 2rem;
}

footer {
  margin-top: 4rem;
  text-align: center;
  color: #777;
}
</style>
