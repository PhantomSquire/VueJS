<template>
  <nav class="navbar">
    <a href="/">HOME</a>
    <a href="/">ROLES</a>
    <a href="/">ABOUT</a>
    <a href="/">GUIDE</a>
    <a href="/">FAQ</a>
    <a href="/">UPDATES</a>
    <a href="/">RESOURCES</a>
    <a href="/">COMMUNITY</a>
    <a href="/">CONTRIBUTE!</a>
  </nav>
</template>

<style scoped>
.navbar {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  background-color: #1e1e1e;
  padding: 1rem;
  justify-content: center;
  border-radius: 10px;
}

.navbar a {
  color: white;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s ease;
}

.navbar a:hover {
  color: #00bfff;
}
</style>
