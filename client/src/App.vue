<template>
  <Navigation userName="Praxis Dr. Regensburg, admin1" />
</template>

<script>
import Navigation from "./components/Navigation.vue";

export default {
  name: "App",
  components: {
    Navigation
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
  padding: 0;
  width: 100vw;
  height: 100vh;
  overflow-x: none;
  overflow-y: scroll;
}

body {
  margin: 0;
  padding: 0;
  font-size: 1.2em;
}
</style>
