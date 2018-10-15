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
