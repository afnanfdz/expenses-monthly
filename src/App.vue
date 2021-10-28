<template>
  <b-card id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
  </b-card>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    
  },
  props: {

  },
};
</script>

<style lang="scss">
@import "~@/assets/scss/vendors/bootstrap-vue/index";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
