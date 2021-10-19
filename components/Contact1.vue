<template>
  <div class="contact">
    <v-row>
      <!-- <v-col cols="12" md="1"></v-col> -->

      <v-col cols="12" md="12" class="col">
        <div v-if="$vuetify.breakpoint.smAndDown" class="infocon">
          <br />
          <div style="text-align: center">
            <span style="color: black">Get In Touch</span>
          </div>

          <br />
          <br />

          <div class="Office">
            <div class="office">
              <v-icon style="color: orange">mdi-map-marker</v-icon>

              <span class="con"
                >Ace Worldwide Limited,6 Roedean Avenue,<br />
                <span style="padding-left: 8%">Enfield, EN3 5QJ</span>
              </span>
            </div>
            <div class="office">
              <v-icon style="color: orange">mdi-phone</v-icon>
              <span class="con">0208 058 1701</span>
            </div>
            <div class="office">
              <v-icon style="color: orange"> mdi-email</v-icon>
              <span class="con"> info@aceworldwide.co.uk</span>
            </div>
          </div>
        </div>
        <div v-if="!$vuetify.breakpoint.smAndDown" style="text-align: center">
          <br />

          <span style="color: black; text-align: center; font-size: 30px"
            >Get in touch</span
          >
        </div>
        <br />
        <div v-if="!$vuetify.breakpoint.smAndDown">
          <v-row>
            <!-- <v-col cols="12" md="1"></v-col> -->
            <v-col cols="12" md="4">
              <div class="office1">
                <v-icon style="color: orange">mdi-map-marker</v-icon>

                <span class="con">
                  Ace Worldwide Limited,<br />
                  6 Roedean Avenue,<br />
                  Enfield, EN3 5QJ
                </span>
              </div>
            </v-col>
            <v-col cols="12" md="4">
              <div class="office1">
                <v-icon style="color: orange">mdi-phone</v-icon>
                <span class="con">0208 058 1701</span>
              </div>
            </v-col>
            <v-col cols="12" md="4">
              <div class="office1">
                <v-icon style="color: orange"> mdi-email</v-icon>
                <span class="con"> info@aceworldwide.co.uk</span>
              </div>
            </v-col>
          </v-row>
        </div>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12" md="12">
        <div v-if="$vuetify.breakpoint.smAndDown">
          <iframe
            class="iframe"
            src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d2474.8150359827437!2d-0.05097705017130872!3d51.66322280702139!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1sAce%20Worldwide%20Limited%2C6%20Roedean%20Avenue%2CEnfield%2CEN3%205QJ!5e0!3m2!1sen!2sin!4v1634381439182!5m2!1sen!2sin"
            width="393"
            height="440"
            style="border: 0"
            allowfullscreen=""
            loading="lazy"
          ></iframe>
        </div>
        <div v-if="!$vuetify.breakpoint.smAndDown">
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d2474.8152177250035!2d-0.05097168422428488!3d51.66321947966109!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1sAce%20Worldwide%20Limited%2C6%20Roedean%20Avenue%2CEnfield%2CEN3%205QJ!5e0!3m2!1sen!2sin!4v1634531087344!5m2!1sen!2sin"
            width="100%"
            height="450px"
            style="border: 0"
            allowfullscreen=""
            loading="lazy"
          ></iframe>
        </div>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {}
</script>

<style>
.con {
  color: rgb(94, 90, 90);
  font-size: 20px;
}
.infocon {
  /* text-align: center; */
  margin-top: 60px;
}
.office1 {
  text-align: center;
}

@media (max-width: 991px) {
  .infocon {
    margin-top: 10px;
  }
  .con {
    font-size: 13px;
    text-align: center;
  }
  .office1 {
    text-align: left;
  }
}
/* .iframe {
  height: 500%;
  width: 500%;
} */
</style>