<template>
  <div id="main-container">
    <h2>Página de Pedidos</h2>
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
</style>
