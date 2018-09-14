<template>
  <div>
    <!-- <img alt="Vue logo" src="../assets/images/logo1.png"> -->
    <plastic-waste></plastic-waste>
  </div>
</template>

<script>
// @ is an alias to /src
import plasticWaste from "@/components/plastic-waste.vue";

export default {
  name: "plastic",
  components: {
    plasticWaste
  }
};
</script>
