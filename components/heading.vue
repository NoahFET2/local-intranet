<template>
  <header>
    <nav>
      <ul>
        <li><nuxt-link to="/">Home</nuxt-link></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
/* Add your header styles here */
header {
  background-color: #333;
  padding: 10px;
}

nav {
  display: flex;
  justify-content: space-between;
}

ul {
  list-style-type: none;
  display: flex;
}

li {
  margin-right: 10px;
}

a {
  color: white;
  text-decoration: none;
}
</style>
