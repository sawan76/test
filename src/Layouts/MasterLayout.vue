<template>
  <div>
    <Navbar />

    <main class="container">
      <slot />
    </main>
  </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";

export default {
  name: "MasterLayout",
  components: {
    Navbar,
  },
};
</script>

<style scoped>
.container {
  padding: 20px;
}

</style>
