<template>
  <div id="app">
    <Input/>
  </div>
</template>

<script>
// import Container from './components/Container.vue'
// import Icon from './components/Icon.vue'
// import Button from './components/Button.vue'
// import Radio from "./components/Radio.vue";
// import CheckBox from "./components/CheckBox.vue";
import Input from "./components/Input.vue";


export default {
  name: "app",
  components: {
    Input
  }
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
