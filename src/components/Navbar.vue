<template>
  <nav class="nav">
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/contact">Contact</router-link>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
.nav {
  display: flex;
  gap: 20px;
  background: #222;
  padding: 15px;
}



a {
  color: white;
  text-decoration: none;
}

.router-link-active {
  font-weight: bold;
  border-bottom: 2px solid #fff;
}


</style>
