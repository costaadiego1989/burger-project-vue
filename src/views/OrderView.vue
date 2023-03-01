<template>
  <div id="main-container">
    <h2>Pedidos Realizados</h2>
    <Dashboard />
  </div>
</template>

<script>
import Dashboard from "../components/Dashboard.vue";

export default {
  name: "OrderView",
  components: {
    Dashboard,
  }
}
</script>

<style scoped>
  h2 {
    text-align: center;
    margin-bottom: 1rem;
    padding: 1rem;
    font-size: 2rem;
  }
</style>
