<template>
  <div style="background-color: black">
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <v-row no-gutters>
        <v-row no-gutters>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/development/bespokedesk.jpg"></v-img>
              <nuxt-link style="text-decoration: none" to="/besdev">
                <v-btn class="one"> Read More </v-btn>
              </nuxt-link>
              <div class="sub-title" align="center">
                <span>Bespoke Developments</span>
              </div>
            </div>
          </v-col>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/construction/bespokedesk.jpg"></v-img>
              <nuxt-link style="text-decoration: none" to="/bescon"
                ><v-btn class="one">Read More</v-btn></nuxt-link
              >
              <div class="sub-title" align="center">
                <span>Bespoke Construction</span>
              </div>
            </div>
          </v-col>
        </v-row>

        <v-row no-gutters>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/interior/bespokedesk.jpg"></v-img>
              <nuxt-link style="text-decoration: none" to="/besint"
                ><v-btn class="one">Read More</v-btn></nuxt-link
              >
              <div class="sub-title" align="center">
                <span>Bespoke Interiors</span>
              </div>
            </div>
          </v-col>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/heritage/bespokedesk.jpg"></v-img>
              <nuxt-link style="text-decoration: none" to="/besher"
                ><v-btn class="one">Read More</v-btn></nuxt-link
              >
              <div class="sub-title" align="center">
                <span>Bespoke Heritage</span>
              </div>
            </div>
          </v-col>
        </v-row>
      </v-row>
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <v-row no-gutters>
        <v-row no-gutters>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/development/bespokemob.jpg"></v-img>
              <nuxt-link style="text-decoration: none" to="/besdev"
                ><v-btn class="one1">Read More</v-btn></nuxt-link
              >
              <div class="sub-title-mob">
                <span>Bespoke Developments</span>
              </div>
            </div>
          </v-col>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/construction/bespokemob.jpg"></v-img>
              <nuxt-link style="text-decoration: none" to="/bescon"
                ><v-btn class="one1">Read More</v-btn></nuxt-link
              >
              <div class="sub-title-mob"><span>Bespoke Construction</span></div>
            </div>
          </v-col>
        </v-row>
        <v-row no-gutters
          ><v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/interior/bespokemob.jpg"></v-img>
              <nuxt-link style="text-decoration: none" to="/besint">
                <v-btn class="one1">Read More</v-btn></nuxt-link
              >
              <div class="sub-title-mob1">
                <span>Bespoke Interiors</span>
              </div>
            </div>
          </v-col>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/heritage/bespokemob.jpg"></v-img>
              <nuxt-link style="text-decoration: none" to="/besher">
                <v-btn class="one1"> Read More</v-btn></nuxt-link
              >
              <div class="sub-title-mob1">
                <span>Bespoke Heritage</span>
              </div>
            </div>
          </v-col></v-row
        >
      </v-row>
    </div>

    <v-divider dark color="orange"></v-divider>
    <br />
  </div>
</template>

<script>
export default {}
</script>

<style>
.sub-title-mob {
  position: relative;
  bottom: 280px;
  left: 14%;
  background-color: white;
  width: 300px;
  font-weight: bold;
  font-size: 18px;
  text-align: center;
}
.sub-title-mob1 {
  position: relative;
  bottom: 280px;
  left: 23%;
  background-color: white;
  width: 220px;
  font-weight: bold;
  font-size: 18px;
  text-align: center;
}
.one {
  position: relative;
  left: 40%;
  bottom: 250px;
  /* background-image: linear-gradient(orange, orange); */
}
.title {
  position: relative;
  left: 15%;
  bottom: 300px;
  font-size: 25px;
  color: black;
  /* text-shadow: 2px 2px white; */
  font-weight: bold;
  background-color: white;

  /* background-image: linear-gradient(orange, orange); */
}
.title5 {
  position: relative;
  left: 10%;
  bottom: 300px;
  font-size: 25px;
  color: black;
  /* text-shadow: 2px 2px white; */
  font-weight: bold;
  background-color: white;
}
.sub-title {
  position: relative;
  width: 300px;
  left: 26%;
  bottom: 335px;
  font-size: 25px;
  color: black;
  /* text-shadow: 4px 4px white; */
  font-weight: bold;
  background-color: white;
}

.inner {
  overflow: hidden;
  height: 400px;
  width: 100%;
}
.img {
  transition: all 1.5s ease;
  height: 100%;
  width: 100%;
}
.inner:hover .img {
  transform: scale(1.1);
}
.one1 {
  position: relative;
  left: 35%;
  bottom: 100px;
}
.title1 {
  /* position: relative;
  left: -2%;
  bottom: 250px;
  font-size: 20px;
  color: black;
  text-shadow: 2px 2px white;
  font-weight: bold;
  background-color: white;

  background-image: linear-gradient(orange, orange); */
}
.title7 {
  /* position: relative;
  left: -7%;
  bottom: 250px;
  font-size: 20px;
  color: black;
  text-shadow: 2px 2px white;
  font-weight: bold;
  background-color: white;

  background-image: linear-gradient(orange, orange); */
}

@media (max-width: 320px) {
  .one1 {
    position: relative;
    left: 25%;
    bottom: 100px;
  }
  .sub-title-mob {
    position: relative;
    left: 3%;
    bottom: 280px;
  }
  .sub-title-mob1 {
    position: relative;
    left: 18%;
    bottom: 280px;
  }
}
@media only screen and (min-device-width: 768px) and (max-device-width: 1024px) {
  .one1 {
    position: relative;
    left: 43%;
    bottom: 100px;
  }
  .sub-title-mob {
    position: relative;
    left: 33%;
    bottom: 280px;
  }
  .sub-title-mob1 {
    position: relative;
    left: 37%;
    bottom: 280px;
  }
}
/* @media only screen and (min-width: 1024px) and (max-height: 1366px) and (orientation: portrait) and (-webkit-min-device-pixel-ratio: 1.5) {
  .title7 {
    position: relative;
    left: 10%;
    bottom: 250px;
  }
} */

@media only screen and (min-width: 1024px) and (max-height: 1366px) and (-webkit-min-device-pixel-ratio: 2) and(orientation: portrait) {
  .title5 {
    position: relative;
    left: 60%;
  }
}
@media only screen and (min-device-width: 1024px) and (max-device-width: 1366px) and (-webkit-min-device-pixel-ratio: 2) and (orientation: landscape) {
  .title5 {
    position: relative;
    left: 60%;
  }
}
</style>