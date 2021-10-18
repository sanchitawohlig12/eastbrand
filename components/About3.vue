<template>
  <div>
    <div v-if="!$vuetify.breakpoint.smAndDown" class="footer">
      <v-row>
        <!-- <v-col cols="12" md="1"></v-col> -->
        <v-spacer></v-spacer>
        <v-col cols="12" md="4" class="col">
          <div class="Ace">
            <img class="logo" src="/services/ACE.svg" alt="" />
            <br />

            <p>
              Our vision was to create a vast unparalleled monopoly of luxurious
              companies, so as we could provide a full suite of development
              services to cater for all of our clienteles pacific needs.
            </p>
          </div>
        </v-col>
        <v-col cols="12" md="3" class="col">
          Information
          <br />
          <br />
          <v-row>
            <v-col cols="12" md="12">
              <div class="info">
                <nuxt-link style="text-decoration: none" to="/home">
                  <p>> <span class="sp">Home</span></p></nuxt-link
                >
              </div>
              <div class="info">
                <nuxt-link style="text-decoration: none" to="/services"
                  ><p>> <span class="sp">Our Services</span></p></nuxt-link
                >
              </div>
              <div class="info">
                <nuxt-link style="text-decoration: none" to="/about"
                  ><p>> <span class="sp">About Us</span></p></nuxt-link
                >
              </div>
              <div class="info">
                <nuxt-link style="text-decoration: none" to="/contact"
                  ><p>> <span class="sp">Contact Us</span></p></nuxt-link
                >
              </div>
            </v-col>
            <!-- <v-col cols="6">
              <div class="info">
                <p>> <span>Our Project</span></p>
              </div>
              <div class="info">
                <p>> <span>About Us</span></p>
              </div>
              <div class="info">
                <p>> <span>Latest News</span></p>
              </div>
              <div class="info">
                <p>> <span>Master Plan</span></p>
              </div>
            </v-col> -->
          </v-row>
        </v-col>
        <v-col cols="12" md="5" class="col">
          Our Office
          <br />
          <br />

          <div class="Office">
            <div class="office">
              <v-icon style="color: orange">mdi-map-marker</v-icon>

              Ace Worldwide Limited,6 Roedean Avenue,Enfield, EN3 5QJ
            </div>
            <div class="office">
              <v-icon style="color: orange">mdi-phone</v-icon>
              0208 058 1701
            </div>
            <div class="office">
              <v-icon style="color: orange"> mdi-email</v-icon>
              info@aceworldwide.co.uk
            </div>
            <!-- <div class="office">
              <v-icon style="color: orange"> mdi-clock-time-nine</v-icon>
              Mon - Sat: 9:00 - 18:00
            </div> -->
          </div>
        </v-col>
      </v-row>
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown" class="footer1">
      <v-row>
        <!-- <v-col cols="12" md="1"></v-col> -->

        <v-col cols="12" class="col">
          <div class="Ace">
            <img class="logo" src="/services/ACE.svg" alt="" />
            <br />

            <p>
              Our vision was to create a vast unparalleled monopoly of luxurious
              companies, so as we could provide a full suite of development
              services to cater for all of our clienteles pacific needs.
            </p>
          </div>
        </v-col>
        <v-col cols="12" md="12" class="col">
          <div class="Ace">
            Information
            <br />
            <br />
            <v-row>
              <v-col cols="12" md="6">
                <div class="info">
                  <nuxt-link style="text-decoration: none" to="/home">
                    <p>> <span class="sp">Home</span></p></nuxt-link
                  >
                </div>
                <div class="info">
                  <nuxt-link style="text-decoration: none" to="/services"
                    ><p>> <span class="sp">Our Services</span></p></nuxt-link
                  >
                </div>
                <div class="info">
                  <nuxt-link style="text-decoration: none" to="/about"
                    ><p>> <span class="sp">About Us</span></p></nuxt-link
                  >
                </div>
                <div class="info">
                  <nuxt-link style="text-decoration: none" to="/contact"
                    ><p>> <span class="sp">Contact Us</span></p></nuxt-link
                  >
                </div>
                <!-- <div class="info">
                  <p>> <span>Our Project</span></p>
                </div>
                <div class="info">
                  <p>> <span>About Us</span></p>
                </div>
                <div class="info">
                  <p>> <span>Latest News</span></p>
                </div>
                <div class="info">
                  <p>> <span>Master Plan</span></p>
                </div> -->
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col cols="12" md="12" class="col">
          <div class="Ace1">
            Our Office
            <br />
            <br />

            <div class="Office">
              <div class="office">
                <v-icon style="color: orange">mdi-map-marker</v-icon>

                Ace Worldwide Limited,6 Roedean Avenue, Enfield, EN3 5QJ
              </div>
              <div class="office">
                <v-icon style="color: orange">mdi-phone</v-icon>
                0208 058 1701
              </div>
              <div class="office">
                <v-icon style="color: orange"> mdi-email</v-icon>
                info@aceworldwide.co.uk
              </div>
              <!-- <div class="office">
                <v-icon style="color: orange"> mdi-clock-time-nine</v-icon>
                Mon - Sat: 9:00 - 18:00
              </div> -->
            </div>
          </div>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.footer {
  background-color: black;
  height: 100%;
  width: 100%;
}
.footer1 {
  background-color: black;
  height: 100%;
  width: 100%;
}
.col {
  color: white;
  font-size: 25px;
  font-weight: bold;
  margin-top: 5px;
}
.col p {
  font-size: 16px;
  font-weight: normal;
  padding-right: 50px;
  color: rgb(241, 232, 232);
  text-align: left;
}
.col1 {
  font-size: 16px;
  font-weight: normal;
  padding-right: 50px;
  color: rgb(241, 232, 232);
}
.info {
  padding-bottom: 20px;
}
.office {
  padding-bottom: 20px;
}
span {
  padding-left: 5px;
}
.sp:hover {
  color: orange;
}
.Office {
  margin-top: -10px;
  font-size: 16px;
  font-weight: normal;
  color: rgb(241, 232, 232);
}
.Ace {
  margin-left: 10px;
}
.Ace1 {
  margin-left: 10px;
  margin-top: -20px;
}
.logo {
  height: 80px;
  width: 150px;
  /* margin-top: 30px; */
  margin-top: 0;
  margin-left: 50px;
}

a:hover {
  color: orange;
}
a.nuxt-link {
  text-decoration: none;
}
@media (max-width: 991px) {
  .logo {
    margin-left: -50px;
  }
}
</style>