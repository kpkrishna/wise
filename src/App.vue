<template>
  <div id="app">
    <CardsPageView />
  </div>
</template>

<script>
import CardsPageView from "./views/CardsPageView";

export default {
  name: "app",
  components: {
    CardsPageView,
  },
};
</script>

<style scoped>
#app {
  /* font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}
</style>
