<template>
  <div id="app">
    <Todolist />
  </div>
</template>

<script>
import Todolist from "./components/todolist/index.vue";

export default {
  name: "App",
  components: {
    Todolist
  }
};
</script>

<style>
body {
  margin: 0;
  background-color: #f0c9cf;
  width: 100vw;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
#app {
  box-sizing: border-box;
  width: calc(100vw - 488px);
}
</style>
