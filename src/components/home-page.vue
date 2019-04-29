<template>
<div>

  <div class="hero">
      <template>
        
        <!-- <div class="home--form animated fadeInLeft">
          <el-form :inline="false" label-position="top" label-width="100px" :model="form" ref="requirements" :rules="rules">
            <el-form-item label="Loan Amount" prop="loan_amount">
              <el-input v-model.number="form.loan_amount" autofocus>
                <template slot="prepend">R</template>
              </el-input>
            </el-form-item>
            <el-form-item label="Registered Company Name" prop="company_name">
              <el-input v-model="form.company_name"></el-input>
            </el-form-item>
            <el-form-item label="Email" prop="email">
              <el-input v-model="form.email"></el-input>
            </el-form-item>
            <el-form-item label="">
              <el-button @click="beginApplication()" type="primary">Get Loan Offers Now</el-button>
            </el-form-item>
          </el-form>
          
        </div> -->
        <div class="__prompt">
          <h1>Supplying the plastics industry with quality products and materials</h1>
          <h3>PolyTherm provides quality plastic recycling products that is tailored to your requirements</h3>
        </div>

        <!-- <div class="wrap-banner">
        <div class="main-title">
          <h1>PolyTherm is dedicated to making the world a better place by creating machinary and cunting edge technology which allows plastic to be recycled and used to fuel the future!</h1>
          <h3>We are dedicated to blah blah blah...</h3>
        </div>
        </div> -->
        <vue-particles class="particles"
        color="#2941f0"
        :particleOpacity="0.7"
        :particlesNumber="80"
        shapeType="circle"
        :particleSize="4"
        linesColor="#2941f0"
        :linesWidth="1"
        :lineLinked="true"
        :lineOpacity="0.4"
        :linesDistance="150"
        :moveSpeed="3"
        :hoverEffect="true"
        hoverMode="grab"
        :clickEffect="true"
        clickMode="push"
      >
      </vue-particles>
       
      </template>
       
    </div>

  <div class="headline __invert">
    <h1>From plastic recycling machinery to plastic extrusion lines and auxiliary machines, PolyTherm has it covered</h1>
    <div class="__cta">
      <router-link to="/about">
        <el-button type="success">About Us</el-button>
      </router-link>
    </div>
  </div>

  

  <div class="why">
    <div class="headline">
    <h1>Welcome to PolyTherm – We offer the best quality machines to customers from around the world</h1>
  </div>
    <div class="__icons">
      
      <div class="__icon" data-aos="fade-right" data-aos-duration="1000" data-aos-delay="100" data-aos-anchor-placement="top-center" data-aos-once="true">
          
      <img src='../assets/images/Granulator.jpg' style="width:100%" alt="Granulator">

        <h2>Plastic Recycling Machinery</h2>
        <p style="text-align:center">
            State of the art plastic recycling machinery. 
        </p>
      </div>

      <div class="__icon" data-aos="fade-right" data-aos-duration="1000" data-aos-delay="50" data-aos-anchor-placement="top-center" data-aos-once="true">
          
      <img src='../assets/images/pet-bottle-washing.jpg' style="width:100%" alt="pet-bottle-washing">

        <h2>Plastic pipe/profile extrusion line</h2>
        <p style="text-align:center">
            High quality plastic regrinds suitable for all your needs.
        </p>
      </div>

      <div class="__icon" data-aos="fade-right" data-aos-duration="1000" data-aos-delay="150" data-aos-anchor-placement="top-center" data-aos-once="true">
          
      <img src='../assets/images/Aglomorator.jpg' style="width:100%" alt="Aglomorator">

        <h2>Plastic Auxilary Machines</h2>
        <p style="text-align:center">
           Superior polymer compounds made to your specifications. 
        </p>
      </div>
      <!-- <div class="__icon" data-aos="fade-right" data-aos-duration="1000" data-aos-delay="200" data-aos-anchor-placement="top-center" data-aos-once="true">
          
      <img src='../assets/images/Single shaft lump shredder.jpg' style="width:100%">

        <h2>We Buy Plastic Scrap</h2>
        <p style="text-align:center">
           We recycle scrap including manufacturers & packaging waste. 
        </p>
      </div> -->
    </div>
  </div>

  <div class="headline __invert">
    <h1>Our <span class="highlight">Products</span></h1>
  </div>

  <div class="partners">
    <el-carousel :interval="4000" type="card" indicator-position="none" arrow="never">
      <el-carousel-item>
        <div class="__partner--demo">
          <div class="__left">
            <p>
              PolyTherm is a professional manufacturer for all kinds of plastic machines which is a blend of researching and developing, designing, manufacturing and operations. We are experts in manufacturing waste plastic recycling machinery, plastic extruders and their auxiliary machines.
            </p>
            <router-link to="/products">
              <el-button type="success" size="tiny">Read More</el-button>
            </router-link>
          </div>
          <div class="offers ">
            <div class="__offer">
              <div class="__logo">
                <img src="../assets/images/pelletizer.jpg" alt="pelletizer">
              </div>
              <div class="__head">
                <h4>Plastic Recycling Machinery</h4>
              </div>
            </div>
          </div>
        </div>
      </el-carousel-item>
      <el-carousel-item>
        <div class="__partner--demo">
          <div class="__left">
            <p>
              PolyTherm operate to industry leading standards when it comes to the fast, efficient and thorough sorting of plastic materials. Utilising both our own staff’s expert knowledge and experience, together with leading edge technology in the form of our purpose built washing and separation plants, our facility is capable of separating, cleaning and sorting a huge range of waste plastics.
            </p>
            <router-link to="/products">
              <el-button type="success" size="tiny">Read More</el-button>
            </router-link>
          </div>
          <div class="offers">
            <div class="__offer">
              <div class="__logo">
                <img src="../assets/images/film squeezer.jpg" alt="film squeezer">
              </div>
              <div class="__head">
                <h4>Plastic Extrusion Line</h4>
              </div>
            </div>
          </div>
        </div>
      </el-carousel-item>
      <el-carousel-item>
        <div class="__partner--demo">
          <div class="__left">
            <p>
              With years of experience in the plastics industry PolyTherm understands that you need the very best quality polymer compounds for your injection, blow & extrusion moulding needs. Our compounding service offers you a viable alternative to the use of virgin plastics – including the added benefits of a cheaper, more cost-effective raw material produced from an environmentally sustainable source – recycled waste or scrap plastics.
            </p>
            <router-link to="/products">
              <el-button type="success" size="tiny">Read More</el-button>
            </router-link>
          </div>
          <div class="offers">
            <div class="__offer">
              <div class="__logo">
                <img src="../assets/images/PEPP-film-washing.jpg" alt="PEPP-film-washing">
              </div>
              <div class="__head">
                <h4>Plastic Auxilary Machines</h4>
              </div>
            </div>
          </div>
        </div>
      </el-carousel-item>
    </el-carousel>
  </div>

  <!-- <div class="headline __invert">
    <div class="__cta">
      <a href="/partners">
        <el-button type="primary">Learn More About Our Partners</el-button>
      </a>
    </div>
  </div> -->

  <div>

  <div class="section">
    <div class="__text">
      <h1>
        Checkout what products we have to offer you
      </h1>
    </div>
    <router-link to="/products">
      <el-button type="success">Products</el-button>
    </router-link>
  </div>

</div>


</div>
</template>

<script>
/* eslint-disable */
export default {
  mounted() {
    window.scrollTo(0,0);
  },
  head() {
    return {
      title: "Home"
    };
  },
  components: {
    //"apply-section": section
  }
};
</script>
