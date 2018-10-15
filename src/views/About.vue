<template>
  <div>
    <!-- <img alt="Vue logo" src="../assets/images/logo1.png"> -->
    <about-us></about-us>
  </div>
</template>

<script>
// @ is an alias to /src
import aboutUs from "@/components/about-us.vue";

export default {
  name: "About",
  components: {
    aboutUs
  }
};
</script>
