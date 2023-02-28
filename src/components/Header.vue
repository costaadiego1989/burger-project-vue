<template>
  <header>
    <nav id="nav">
      <router-link to="/"><img :src="logo" :alt="website_title" id="logo" /></router-link>
      <router-link to="/">Home</router-link> |
      <router-link to="/pedidos">Pedidos</router-link>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: ["logo", "website_title"],
};
</script>

<style scoped>
  #nav {
    background-color: #222;
    border-bottom: 4px solid #111;
    padding: 15px 50px;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }
  #nav #logo-url {
    margin: auto;
    margin-left: 0;
  }
  #logo {
    width: 40px;
    height: 40px;
  }
  #nav a {
    color: #fcba03;
    text-decoration: none;
    margin: 12px;
    transition: .5s;
  }
  #nav a:hover {
    color: #FFF;
  }
</style>