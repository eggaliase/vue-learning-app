<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" width="25%" />
    <Messages msg="Hello Vue in CodeSandbox!" />
  </div>
</template>

<script>
import Messages from "./components/Messages.vue";

export default {
  name: "App",
  components: {
    Messages,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
