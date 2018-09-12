<template>
  <div>
    <!-- <img alt="Vue logo" src="../assets/images/logo1.png"> -->
    <home-page></home-page>
  </div>
</template>

<script>
// @ is an alias to /src
import homePage from "@/components/home-page.vue";

export default {
  name: "home",
  components: {
    homePage
  }
};
</script>
