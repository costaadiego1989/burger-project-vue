<template>
    <footer id="footer">
        <p>Make Your Burger &copy; {{ this.year }}</p>
    </footer>
  </template>
  
  <script>
  export default {
      name: "Footer",
      data() {
        return {
            year: new Date().getFullYear()
        }
      }
  }
  </script>

<style scoped>
#footer {
  height: 100px;
  background-color: #222;
  border-top: 4px solid #111;
  color: #fcba03;
  display: flex;
  align-items: center;
  justify-content: center;
  bottom: 0;
  width: 100%;
}
</style>