<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <component-1> </component-1>
</template>

<script>
import Component1 from './components/Component1.vue';
export default {
  name: "App",
  components: {
    Component1,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
