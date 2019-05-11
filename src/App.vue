<template>
  <div id="app">
    <div class="poly">
      <nav-bar></nav-bar>
    <router-view/>
    <main-footer></main-footer>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import navBar from "@/components/navbar.vue";
import mainFooter from "@/components/main-footer.vue";

export default {
  name: "master",
  components: {
    navBar,
    mainFooter
  }
};
</script>

<style lang="scss">
@import "./src/assets/scss/app.scss";
</style>
