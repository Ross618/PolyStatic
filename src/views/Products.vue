<template>
  <div>
    <!-- <img alt="Vue logo" src="../assets/images/logo1.png"> -->
    <all-products></all-products>
  </div>
</template>

<script>
// @ is an alias to /src
import allProducts from "@/components/all-products.vue";

export default {
  name: "Products",
  components: {
    allProducts
  }
};
</script>
