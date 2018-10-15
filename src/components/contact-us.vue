<template>
<div>
  <!-- <div class="headline __invert">
    <h1>We Make Business Loan Applications <span class="highlight">Easy & Smart</span></h1>
    <div class="__cta">
      <nuxt-link to="/apply">
        <el-button type="success">Apply For A Business Loan</el-button>
      </nuxt-link>
    </div>
  </div> -->
  <div class="contact">
    <div class="container">
      <div class="application __sit">
        <div class="__form" >
          <div class="__title">
            <h1>Contact Us</h1>
          </div>
          <el-form :inline="false" label-position="top" label-width="100px" :model="form" ref="requirements" :rules="rules">
            <div class="__steps">
              <div class="__step"  >
                <div class="__body">
                  <div class="__col">
                    <el-form-item label="Subject" prop="subject">
                      <el-input v-model="form.subject" autofocus></el-input>
                    </el-form-item>
                  </div>
                  
                  <!-- <div class="__col">
                    <el-form-item label="Email" prop="email">
                      <el-input v-model="form.email"></el-input>
                    </el-form-item>
                  </div> -->

                  <div class="__col __full">
                    <el-form-item label="Message" prop="message">
                      <el-input :rows="4" type="textarea" v-model="form.message"></el-input>
                    </el-form-item>
                  </div>
                  <div class="__col __full __cta">
                    <el-form-item >
                      <el-button type="success" @click="contact()">Submit</el-button>
                    </el-form-item>
                  </div>
                </div>
              </div>
            </div>
          </el-form>
        </div>
      </div>
    </div>
  </div>
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
              PolyTherm is a professional manufacturer for all kinds of plastic machines which is a blend of researching and developing, designing, manufacturing and operations. We are experts in manufacturing waste plastic recycling machinery, plastic extruders and their auxiliary machines.
            </p>
          </div>
        </div>
        
      </div>
    </div>
</div>
</template>

<script>
//import axios from "axios";
/* eslint-disable */

export default {
  head() {
    return {
      title: "Contact"
    };
  },
  data() {
    return {
      test: "asdas",
      form: {
        subject: "",
        message: ""
      },
      rules: {
        // email: [
        //   {
        //     type: "email",
        //     required: true,
        //     message: "enter a valid email address",
        //     trigger: "change, blur"
        //   }
        // ],
        subject: [
          {
            required: true,
            message: "enter a subject",
            trigger: "change, blur"
          }
        ],
        message: [
          {
            required: true,
            message: "enter a message",
            trigger: "change, blur"
          }
        ]
      }
    };
  },
  mounted() {
    // window.scroll({
    //   top: 500,
    //   left: 0,
    //   behavior: "smooth"
    // });
  },
  components: {

  },
  methods: {

    contact() {
      window.location.href = "mailto:grant.wise@live.com?subject=" + this.form.subject + "&body=" + this.form.message +  "";
    }

    // contact() {
    //       axios({
    //         method: 'post',
    //         url: `https://api.mailgun.net/v3/sandbox1486aec5e16b4c5fbcb61c03fd81241f.mailgun.org/messages`,
    //         auth: {
    //             username: 'api',
    //             password: mailgun.apiKey
    //         },
    //         params: {
    //             from: 'Awesome Development Team <noreply@yourdomain.com>',
    //             to: 'rossp1618@gmail.com',
    //             subject: 'Hello',
    //             text: 'Welcome to the team!'
    //         }
    //     }).then(
    //         response => {
    //             console.log(response)
    //         },
    //         reject => {
    //             console.log(reject)
    //         }
    //     )
    // },

    
  }
};
</script>

<style>

</style>
