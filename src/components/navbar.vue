<template>
<div>
  <nav class="navbar navbar-light navbar-fixed-top bg-faded ">
    <div class="__logo a1 fadeIn">
      <a href="/">
      <img src="../assets/images/logo2.png" style="width:60px;height:60px;" alt="Poly Logo">
        <img src="../assets/images/PolyText2.png" style="width:160px;height:50px;padding-bottom:5px;" alt="Poly Logo">
      </a>

    </div>
    <div class="__links a1 fadeIn">
      <router-link to="/services">Services</router-link>
      <router-link to="/products">Products</router-link>
      <router-link to="/gallery">Gallery</router-link>
      <router-link to="/plastic">Plastic Waste</router-link>
      <router-link to="/contact">Contact Us</router-link>
    </div>
  </nav>
  <div class="toggle" :class="{ '__visible' : sideBarVisible === true }">
    <i class="material-icons" @click="toggleSidebar()">menu</i>
  </div>
  <div class="sidebar" :class="{ '__visible' : sideBarVisible === true }">
    <div class="__items">
      <div class="__item">
        <router-link to="/">Home</router-link>
      </div>
      <div class="__item">
        <router-link to="/services">Services</router-link>
      </div>
      <div class="__item">
        <router-link to="/products">Products</router-link>
      </div>
      <div class="__item">
        <router-link to="/gallery">Gallery</router-link>
      </div>
      <div class="__item">
        <router-link to="/plastc">Plastic Waste</router-link>
      </div>
      <div class="__item">
        <router-link to="/contact">Contact Us</router-link>
      </div>
    </div>
  </div>
</div>
</template>

<script>
/* eslint-disable */
export default {
  data() {
    return {
      sideBarVisible: false
    };
  },

  methods: {
    /**
     * Toggle Mobile Sidebar
     * @return
     */
    toggleSidebar() {
      this.sideBarVisible = !this.sideBarVisible;
    }
  }
};
</script>
