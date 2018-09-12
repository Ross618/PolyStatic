<template>
<div>
  <nav class="navbar navbar-light navbar-fixed-top bg-faded ">
    <div class="__logo">
      <a href="/">
      <img src="../assets/images/logo2.png" style="width:60px;height:60px;" alt="Poly Logo">
        <img src="../assets/images/PolyText2.png" style="width:160px;height:50px;padding-bottom:5px;" alt="Poly Logo">
      </a>

    </div>
    <div class="__links a1 fadeIn">
      <a href="/about">About Us</a>
      <a href="/faq">FAQs</a>
      <a href="/partners">Partners</a>
      <a href="/contact">Contact Us</a>
    </div>
  </nav>
  <div class="toggle" :class="{ '__visible' : sideBarVisible === true }">
    <i class="material-icons" @click="toggleSidebar()">menu</i>
  </div>
  <div class="sidebar" :class="{ '__visible' : sideBarVisible === true }">
    <div class="__items">
      <div class="__item">
        <a href="/">Home</a>
      </div>
      <div class="__item">
        <a href="/about">About Us</a>
      </div>
      <div class="__item">
        <a href="/faq">FAQs</a>
      </div>
      <div class="__item">
        <a href="/partners">Partners</a>
      </div>
      <div class="__item">
        <a href="/contact">Contact Us</a>
      </div>
    </div>
  </div>
</div>
</template>

<script>
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
