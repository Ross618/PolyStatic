<template>
  <div>
    <!-- <img alt="Vue logo" src="../assets/images/logo1.png"> -->
    <gallery1></gallery1>
  </div>
</template>

<script>
// @ is an alias to /src
import gallery1 from "@/components/gallery1.vue";

export default {
  name: "Gallery",
  components: {
    gallery1
  }
};
</script>
