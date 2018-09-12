<template>
  <div id="app">
    <div class="poly">
      <nav-bar></nav-bar>
    <router-view/>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import navBar from "@/components/navbar.vue";

export default {
  name: "master",
  components: {
    navBar
  }
};
</script>

<style lang="scss">
@import "./src/assets/scss/app.scss";
</style>
