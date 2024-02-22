<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <a href="https://www.bluehealthethiopia.com" target="_blank">
        <v-img
          src="../assets/bluehealth.png"
          class="my-3"
          contain
          height="100"
        />
        </a>
      </v-col>

      <v-col class="mb-4">
        <p class="white--text subheading font-weight-regular">
          Thank you for your interest to contact us
          <br>you can reach us on any of the following social media. 
        </p>


        <v-row>
          <v-col>
    
            <a href="https://www.linkedin.com/company/blue-health-ethiopia" target="_blank">
            <v-card  color="#005983" class="socialcard mx-auto px-6 py-8 mb-2" max-width="390" height="100">
              <h3 class="facebooktxt display-1 font-weight-bold mb-3">
                Linkedin
              </h3>
            </v-card>
            </a>

            <a href="https://www.instagram.com/bluehealthethiopia" target="_blank">
            <v-card class="instagram socialcard mx-auto px-6 py-8 mb-2" max-width="390" height="100">
              <h3 class="facebooktxt display-1 font-weight-bold mb-3">
                Instagram
              </h3>
            </v-card>
            </a>

            <a href="https://www.tiktok.com/@bluehealthethiopia" target="_blank">
            <v-card color="#000000" class="socialcard mx-auto px-6 my-5 mb-2" max-width="390" height="100">
              <v-row class="text-center">
                <v-col cols="6">
                  <v-img
                    src="../assets/tiktok.png"
                    contain
                    height="80"
                  />
                </v-col>
                <v-col cols="6">
                  <h3 class="tiktoktext display-1 font-weight-bold mt-6 mb-3">
                    TikTok
                  </h3>
                </v-col>
              </v-row>
            </v-card>
            </a>

            <a href="https://www.youtube.com/@bluehealthethiopia" target="_blank">
              <v-card color="#FF0000" class="socialcard mx-auto px-6 py-2 mb-2" max-width="390" height="100">
                    <v-img
                      src="../assets/yt.png"
                      contain
                      height="80"
                    />
              </v-card>
            </a>
          </v-col>

          <v-col>
            

            <a href="https://t.me/bluehealthethiopia" target="_blank">
            <v-card  color="#0A739F" class="socialcard mx-auto px-6 py-8 mb-2" max-width="390" max-height="100">
              <h3 class="facebooktxt display-1 font-weight-bold mb-3">
                Telegram
              </h3>
            </v-card>
            </a>

            <a href="https://www.facebook.com/bluehealthethiopia" target="_blank">
              <v-card color="#485A96" class="socialcard mx-auto px-6 py-8 mb-2" max-width="390" height="100">
                <h3 class="facebooktxt display-1 font-weight-bold mb-3">
                  Facebook
                </h3>
              </v-card>
            </a>
            <a href="https://twitter.com/bluehealthethiopia" target="_blank">
              <v-card color="#000000" class="socialcard mx-auto px-6 py-4 mb-2" max-width="390" height="100">
                  <v-img
                    src="../assets/xpng.png"
                    contain
                    height="80"
                  />
              </v-card>
            </a>

            <a href="hhttps://www.bluehealthethiopia.com" target="_blank">
              <v-card color="#FFCC00" class="socialcard   mx-auto px-6 py-8 mb-2" max-width="390" height="100">
                <h3 class="facebooktxt display-1 font-weight-bold mb-3">
                  Check our website
                </h3>
              </v-card>
            </a>
          </v-col>
        </v-row>

      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
    }),
  }
</script>
<style>
.facebooktxt {
  /* color: #136587;  */
  color: #FFFFFF; 
}
.websitetext {
  /* color: #136587;  */
  color: #FFCC00; 
}

.instagram{
  background: #f09433; 
  background: -moz-linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%); 
  background: -webkit-linear-gradient(45deg, #f09433 0%,#e6683c 25%,#dc2743 50%,#cc2366 75%,#bc1888 100%); 
  background: linear-gradient(45deg, #f09433 0%,#e6683c 25%,#dc2743 50%,#cc2366 75%,#bc1888 100%); 
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f09433', endColorstr='#bc1888',GradientType=1 );
  }

.tiktoktext{
    text-align: start;
    color: #FFFFFF; 
  }

.socialcard:hover {
  filter: drop-shadow(0 0 0px rgb(255, 255, 255, 60%));
  color: rgb(255, 255, 255, 80%);
  height: 95px;
  width: 370px;
  box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.22);
}

a {
  text-decoration: none;
}
</style>