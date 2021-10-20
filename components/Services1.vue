<template>
  <div style="background-color: black">
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <v-row no-gutters>
        <v-col cols="12" md="6">
          <div class="inner">
            <v-img class="img" src="/development/bespokedesk.jpg"></v-img>

            <nuxt-link style="text-decoration: none" to="/besdev"
              ><v-btn class="two">Read More</v-btn></nuxt-link
            >
            <div class="sub-title1" align="center">
              <span>Bespoke Developments</span>
            </div>
          </div>
        </v-col>
        <v-col cols="12" md="6">
          <div class="inner">
            <v-img class="img" src="/construction/bespokedesk.jpg"></v-img>
            <nuxt-link style="text-decoration: none" to="/bescon"
              ><v-btn class="two">Read More</v-btn></nuxt-link
            >
            <div class="sub-title1" align="center">
              <span>Bespoke Construction </span>
            </div>
          </div>
        </v-col>

        <v-col cols="12" md="6">
          <div class="inner">
            <v-img class="img" src="/interior/bespokedesk.jpg"></v-img>
            <nuxt-link style="text-decoration: none" to="/besint"
              ><v-btn class="two">Read More</v-btn></nuxt-link
            >
            <div class="sub-title1" align="center">
              <span>Bespoke Interiors</span>
            </div>
          </div>
        </v-col>
        <v-col cols="12" md="6">
          <div class="inner">
            <v-img class="img" src="/heritage/bespokedesk.jpg"></v-img>
            <nuxt-link style="text-decoration: none" to="/besher"
              ><v-btn class="two">Read More</v-btn></nuxt-link
            >
            <div class="sub-title1" align="center">
              <span>Bespoke Heritage</span>
            </div>
          </div>
        </v-col>
        <v-col cols="12" md="6">
          <div class="inner">
            <v-img class="img" src="/kitchen/bespokedesk.jpg"></v-img>
            <nuxt-link style="text-decoration: none" to="/beskit">
              <v-btn class="two">Read More</v-btn></nuxt-link
            >
            <div class="sub-title1" align="center">
              <span>Bespoke Kitchen</span>
            </div>
          </div>
        </v-col>
        <v-col cols="12" md="6">
          <div class="inner">
            <v-img class="img" src="/bathroom/bespokedesk.jpg"></v-img>
            <nuxt-link style="text-decoration: none" to="/besbat">
              <v-btn class="two">Read More</v-btn></nuxt-link
            >
            <div class="sub-title1" align="center">
              <span>Bespoke Bathroom</span>
            </div>
          </div>
        </v-col>
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
              <span class="title7">Bespoke Developments</span>
            </div>
          </v-col>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/construction/bespokemob.jpg"></v-img>
              <nuxt-link style="text-decoration: none" to="/bescon"
                ><v-btn class="one1">Read More</v-btn></nuxt-link
              >
              <span class="title7">Bespoke Construction </span>
            </div>
          </v-col>
        </v-row>

        <v-row no-gutters>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/interior/bespokemob.jpg"></v-img>
              <nuxt-link style="text-decoration: none" to="/besint"
                ><v-btn class="one1">Read More</v-btn></nuxt-link
              >
              <span class="title4">Bespoke Interiors</span>
            </div>
          </v-col>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/heritage/bespokemob.jpg"></v-img>
              <nuxt-link style="text-decoration: none" to="/besher"
                ><v-btn class="one1">Read More</v-btn></nuxt-link
              >
              <span class="title4">Bespoke Heritage</span>
            </div>
          </v-col>
        </v-row>
        <v-row no-gutters>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/kitchen/bespokedesk.jpg"></v-img>
              <nuxt-link style="text-decoration: none" to="/beskit">
                <v-btn class="one1">Read More</v-btn></nuxt-link
              >
              <span class="title4">Bespoke Kitchen</span>
            </div>
          </v-col>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/bathroom/bespokemob.jpg"></v-img>
              <nuxt-link style="text-decoration: none" to="/besbat">
                <v-btn class="one1">Read More</v-btn></nuxt-link
              >
              <span class="title4">Bespoke Bathroom</span>
            </div>
          </v-col>
        </v-row>
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
.two {
  position: relative;
  left: 35%;
  bottom: 250px;
}

.inner {
  overflow: hidden;
  /* height: 100%;
  width: 100%; */
}
.img {
  transition: all 1.5s ease;
  /* height: 100%; */
}
.inner:hover .img {
  transform: scale(1.1);
}
/* .one1 {
  position: relative;
  left: 35%;
  bottom: 200px;
} */
.title3 {
  position: relative;
  /* right: 10%; */
  left: 10%;
  bottom: 300px;
  font-size: 25px;
  color: black;
  text-shadow: 2px 2px white;
  font-weight: bold;
  background-color: white;

  /* background-image: linear-gradient(orange, orange); */
}
.sub-title1 {
  position: relative;
  width: 300px;
  left: 22%;
  bottom: 335px;
  font-size: 25px;
  color: black;
  text-shadow: 4px 4px white;
  font-weight: bold;
  background-color: white;
}
.title6 {
  position: relative;
  /* right: 10%; */
  left: 7%;
  bottom: 300px;
  font-size: 25px;
  color: black;
  text-shadow: 2px 2px white;
  font-weight: bold;
  background-color: white;

  /* background-image: linear-gradient(orange, orange); */
}
.title4 {
  position: relative;
  /* right: 10%; */
  right: 2%;
  bottom: 250px;
  font-size: 20px;
  color: black;
  text-shadow: 2px 2px white;
  font-weight: bold;
  background-color: white;

  /* background-image: linear-gradient(orange, orange); */
}
/* .img1 {
  height: 800px;
} */
@media (max-width: 320px) {
  .title4 {
    position: relative;
    /* right: 10%; */
    right: 11%;
    bottom: 250px;
  }
}
@media only screen and (min-device-width: 768px) and (max-device-width: 1024px) {
  .title4 {
    position: relative;
    /* right: 10%; */
    left: 23%;
    bottom: 250px;
  }
}
</style>