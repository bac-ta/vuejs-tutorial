<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Login buttonName="Bac dep zai"/>
  </div>
</template>

<script>
import Login from "./pages/Auth/Login";

export default {
  name: 'app',
  components: {
    Login
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
