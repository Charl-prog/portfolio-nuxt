<template>
  <div>
    <nav>
      <ul>
        <li><NuxtLink to="/">Accueil</NuxtLink></li>
        <li><NuxtLink to="/about">À propos</NuxtLink></li>
        <li><NuxtLink to="/projects">Projets</NuxtLink></li>
      </ul>
    </nav>
    <NuxtPage />
  </div>
</template>

<style scoped>
nav ul {
  list-style-type: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 15px;
}
</style>
