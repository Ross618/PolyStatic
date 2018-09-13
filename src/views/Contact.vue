<template>
  <div>
    <!-- <img alt="Vue logo" src="../assets/images/logo1.png"> -->
    <contact-us></contact-us>
  </div>
</template>

<script>
// @ is an alias to /src
import contactUs from "@/components/contact-us.vue";

export default {
  name: "contact",
  components: {
    contactUs
  }
};
</script>
