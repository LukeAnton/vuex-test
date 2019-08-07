<template>
  <div id="app">
    <div class="container">
      <Todos />
    </div>
  </div>
</template>

<script>
import Todos from "./components/Todos";
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "app",
  components: {
    HelloWorld,
    Todos
  }
};
</script>

<style>
@import "./sass/app.scss";
</style>
