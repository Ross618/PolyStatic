<template>
  <div>
    <home-page></home-page>
    <!-- <img alt="Vue logo" src="../assets/images/logo1.png"> -->
    <!-- <maintenance></maintenance> -->
  </div>
</template>

<script>
// @ is an alias to /src
import homePage from "@/components/home-page.vue";
import maintenance from "@/components/maintenance.vue";

export default {
  name: "home",
  components: {
    homePage,
    maintenance
  }
};
</script>
