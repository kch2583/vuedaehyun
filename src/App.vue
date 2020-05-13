<template>
  <div id="app">
    <logoMenu></logoMenu>
  </div>
</template>

<script>
import logoMenu from "./components/defaultPage/logoMenu";

export default {
  name: "App",
  components: {
    logoMenu
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
