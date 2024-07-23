<template>
  <nav>
    <h1>My Navbar</h1>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
</template>

<script setup>
// You can add any logic or data here if needed
</script>

<style scoped>
nav {
  background-color: #333;
  color: white;
  padding: 1rem;
}

ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

li {
  display: inline-block;
  margin-right: 20px;
}

a {
  color: white;
  text-decoration: none;
}
</style>