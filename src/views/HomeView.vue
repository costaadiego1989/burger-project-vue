<template>
  <div>
    <Banner />
    <div id="main-container">
      <h1>Monte Seu Burger</h1>
    </div>
  </div>
</template>

<script>
import Banner from "../components/Banner.vue";

export default {
  name: "HomeView",
  components: {
    Banner,
  },
};
</script>
