<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Здесь могла быть ваша реклама" />
    <Calculator />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Calculator from "./components/calculator.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Calculator,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
