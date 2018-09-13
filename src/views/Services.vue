<template>
  <div>
    <!-- <img alt="Vue logo" src="../assets/images/logo1.png"> -->
    <all-services></all-services>
  </div>
</template>

<script>
// @ is an alias to /src
import allServices from "@/components/all-services.vue";

export default {
  name: "Services",
  components: {
    allServices
  }
};
</script>
