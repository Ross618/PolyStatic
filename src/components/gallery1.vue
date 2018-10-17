<template>

<div class="page" style="background-color: #E4E4E4;">
  <div class="box">
      <div class="__content" style="text-align:center">
        <h1><span class="highlight">Product Gallery</span></h1>
        <p style="font-size: 1.4rem;">
          PolyTherm offers several products from plastic recycling machinery, extrusion lines and auxilary machines.
           Checkout some of our products below.
        </p>
      </div>
    </div>
  <div class="__gallery">
    <img class="__images" v-for="(image, i) in images" :src="image" @click="onClick(i)">
    <vue-gallery-slideshow :images="images" :index="index" @close="index = null"></vue-gallery-slideshow>
  </div>
</div>
  
</template>

<script>
/* eslint-disable */
import VueGallerySlideshow from 'vue-gallery-slideshow';

export default {
  
  components: {
    VueGallerySlideshow
  },
  methods: {
    onClick(i) {
      this.index = i;
    }
  },
  data() {
    return{
      images: [
      require('../assets/images/aus/1.jpg'),
      require('../assets/images/aus/2.jpg'),
      require('../assets/images/aus/3.jpg'),
      require('../assets/images/aus/4.jpg'),
      require('../assets/images/aus/5.jpg'),
      require('../assets/images/aus/6.jpg'),
      require('../assets/images/aus/7.jpg'),
      require('../assets/images/aus/8.jpg'),
      require('../assets/images/aus/9.jpg'),
      require('../assets/images/aus/10.jpg'),
      require('../assets/images/aus/11.jpg'),
      require('../assets/images/aus/12.jpg'),
      require('../assets/images/aus/13.jpg'),
      require('../assets/images/aus/14.jpg'),
      require('../assets/images/aus/15.jpg'),
      require('../assets/images/aus/16.jpg'),
      require('../assets/images/aus/17.jpg'),
      require('../assets/images/aus/18.jpg'),
      require('../assets/images/aus/19.jpg'),
      require('../assets/images/aus/20.jpg'),
      require('../assets/images/aus/21.jpg'),
      require('../assets/images/aus/22.jpg'),
      require('../assets/images/aus/23.jpg'),
      require('../assets/images/aus/24.jpg'),
      require('../assets/images/pet-bottle-washing.jpg'),
      require('../assets/images/Label remover 1.jpg'),
      require('../assets/images/label remover 2.jpg'),
      require('../assets/images/label remover 3.jpg'),
      require('../assets/images/label remover 4.jpg'),
      require('../assets/images/pelletizer.jpg'),
      require('../assets/images/PEPP-film-washing.jpg'),
      require('../assets/images/vertical dewaterizer.jpg'),
      require('../assets/images/double shaft shredder.jpg'),
      require('../assets/images/Granulator.jpg'),
      require('../assets/images/Aglomorator.jpg'),
    ],
    index: null
    } 
  }
}
</script>
