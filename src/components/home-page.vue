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
          <h1>Supplying the plastics industry with quality services and materials</h1>
          <h3>Expert plastic recycling services tailored to your requirements</h3>
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
    <h1>From colour sorting and separation to polymer compounding, PolyTherm has it covered</h1>
    <div class="__cta">
      <router-link to="/services">
        <el-button type="success">Services</el-button>
      </router-link>
    </div>
  </div>

  

  <div class="why">
    <div class="headline">
    <h1>Welcome to PolyTherm – A leading South African plastic waste recycler</h1>
  </div>
    <div class="__icons">
      <div class="__icon">
          
      <img src='../assets/images/Film shredder.jpg' style="width:100%">

        <h2>Regrinds</h2>
        <p style="text-align:center">
            High quality plastic regrinds suitable for all your needs.
        </p>
      </div>
      <div class="__icon">
          
      <img src='../assets/images/Granulator.jpg' style="width:100%">

        <h2>Separation</h2>
        <p style="text-align:center">
            State of the art separation technology – even by colour! 
        </p>
      </div>
      <div class="__icon">
          
      <img src='../assets/images/Aglomorator.jpg' style="width:100%">

        <h2>Compounds</h2>
        <p style="text-align:center">
           Superior polymer compounds made to your specifications. 
        </p>
      </div>
      <div class="__icon">
          
      <img src='../assets/images/Single shaft lump shredder.jpg' style="width:100%">

        <h2>We Buy Plastic Scrap</h2>
        <p style="text-align:center">
           We recycle scrap including manufacturers & packaging waste. 
        </p>
      </div>
    </div>
  </div>

  <div class="headline __invert">
    <h1>Our <span class="highlight">Services</span></h1>
  </div>

  <div class="partners">
    <el-carousel :interval="4000" type="card" height="500px" indicator-position="none" arrow="never">
      <el-carousel-item>
        <div class="__partner--demo">
          <div class="__left">
            <p>
              Upon arrival at our dedicated recycling facility all waste plastics are hand sorted by our expert staff into material types ready for reprocessing. 
              Once sorted the raw waste plastics are reduced in size by our shredding and granulating machinery. These machines are capable of processing any size of materials...
            </p>
            <router-link to="/services">
              <el-button type="success" size="tiny">Read More</el-button>
            </router-link>
          </div>
          <div class="offers ">
            <div class="__offer">
              <div class="__logo">
                <img src="../assets/images/pelletizer.jpg" alt="Rc Loans">
              </div>
              <div class="__head">
                <h4>Size Reduction</h4>
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
            <router-link to="/services">
              <el-button type="success" size="tiny">Read More</el-button>
            </router-link>
          </div>
          <div class="offers">
            <div class="__offer">
              <div class="__logo">
                <img src="../assets/images/film squeezer.jpg" alt="Lualend">
              </div>
              <div class="__head">
                <h4>Separation</h4>
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
            <router-link to="/services">
              <el-button type="success" size="tiny">Read More</el-button>
            </router-link>
          </div>
          <div class="offers">
            <div class="__offer">
              <div class="__logo">
                <img src="../assets/images/film-bags.jpg" alt="Genfin SVG">
              </div>
              <div class="__head">
                <h4>Compounding</h4>
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
        Checkout what services we have to offer South Africa
      </h1>
    </div>
    <router-link to="/services">
      <el-button type="success">Services</el-button>
    </router-link>
  </div>

  <div>
    <div class="footer">
      <div class="container">
        <div class="__logo">
          <a href="/">
            <img src="../assets/images/logo1.png" style="width:80px;height:80px;" alt="PolyTherm Logo">
            <img src="../assets/images/PolyText.png" style="width:200px;height:60px; padding-bottom: 10px;" alt="PolyTherm Logo">
          </a>
        </div>
        <!-- <h6>
          Copyright <a href="/">PolyTherm</nuxt-link> {{ getYear() }}
        </h6> -->
        <div class="__duo">
          <div class="__links">
            <router-link to="/services">Services</router-link>
            <router-link to="/plastic">Plastic Waste</router-link>
            <router-link to="/contact">Contact Us</router-link>
          </div>
          <div class="__links">
            <p style="padding: 0 0 10px 10px;">
              <i class="material-icons">call</i>
              079 401 2282
            </p>
            <p style="padding: 0 0 10px 10px;">
              <i class="material-icons">mail</i>
              <a href="mailto:info@polytherm.co.za">Email us</a>
            </p>
          </div>
          <div class="__disclaimer">
            <p>
              PolyTherm supplies the plastics industry with quality services and materials
              THIS IS PLACE HOLDER TEXT..
              Let me know what wording you would like in the footer section.
              blah blah blah blah blah blah blah blah blah blah blah blah
              blah blah blah blah blah blah blah blah blah blah blah blah
              blah blah blah blah blah blah blah blah blah blah blah blah
            </p>
          </div>
        </div>
        
      </div>
    </div>
  </div>

</div>


</div>
</template>

<script>
export default {
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
