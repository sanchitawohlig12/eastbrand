<template>
  <div>
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <v-row no-gutters>
        <v-col cols="12" md="6">
          <div class="inner">
            <v-img
              class="img"
              src="/development/bespokedesk.jpg"
              height="100%"
              width="100%"
            ></v-img>
          </div>

          <nuxt-link style="text-decoration: none" to="/besdev"
            ><v-btn class="two">Read More</v-btn></nuxt-link
          >
          <span class="title3">Bespoke Developments</span>
        </v-col>
        <v-col cols="12" md="6">
          <div class="inner">
            <v-img
              class="img"
              src="/construction/bespokedesk.jpg"
              height="100%"
              width="100%"
            ></v-img>
          </div>
          <nuxt-link style="text-decoration: none" to="/bescon"
            ><v-btn class="two">Read More</v-btn></nuxt-link
          >
          <span class="title3">Bespoke Construction </span>
        </v-col>

        <v-col cols="12" md="6">
          <div class="inner">
            <v-img
              class="img"
              src="/interior/bespokedesk.jpg"
              height="100%"
              width="100%"
            ></v-img>
          </div>
          <nuxt-link style="text-decoration: none" to="/besint"
            ><v-btn class="two">Read More</v-btn></nuxt-link
          >
          <span class="title3">Bespoke Interiors</span>
        </v-col>
        <v-col cols="12" md="6">
          <div class="inner">
            <v-img
              class="img"
              src="/heritage/bespokedesk.jpg"
              height="100%"
              width="100%"
            ></v-img>
          </div>
          <nuxt-link style="text-decoration: none" to="/besher"
            ><v-btn class="two">Read More</v-btn></nuxt-link
          >
          <span class="title3">Bespoke Heritage</span>
        </v-col>
        <v-col cols="12" md="6">
          <div class="inner">
            <v-img
              class="img"
              src="/kitchen/bespokedesk.jpg"
              height="100%"
              width="100%"
            ></v-img>
          </div>
          <nuxt-link style="text-decoration: none" to="/beskit">
            <v-btn class="two">Read More</v-btn></nuxt-link
          >
          <span class="title3">Bespoke Kitchen</span>
        </v-col>
        <v-col cols="12" md="6">
          <div class="inner">
            <v-img
              class="img"
              src="/bathroom/bespokedesk.jpg"
              height="100%"
              width="100%"
            ></v-img>
          </div>
          <nuxt-link style="text-decoration: none" to="/besbat">
            <v-btn class="two">Read More</v-btn></nuxt-link
          >
          <span class="title3">Bespoke Bathroom</span>
        </v-col>
      </v-row>
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <v-row no-gutters>
        <v-row no-gutters>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/development/bespokemob.jpg"></v-img>
            </div>

            <nuxt-link style="text-decoration: none" to="/besdev"
              ><v-btn class="one1">Read More</v-btn></nuxt-link
            >
            <span class="title4">Bespoke Developments</span>
          </v-col>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/construction/bespokemob.jpg"></v-img>
            </div>
            <nuxt-link style="text-decoration: none" to="/bescon"
              ><v-btn class="one1">Read More</v-btn></nuxt-link
            >
            <span class="title4">Bespoke Construction </span>
          </v-col>
        </v-row>

        <v-row no-gutters>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/interior/bespokemob.jpg"></v-img>
            </div>
            <nuxt-link style="text-decoration: none" to="/besint"
              ><v-btn class="one1">Read More</v-btn></nuxt-link
            >
            <span class="title4">Bespoke Interiors</span>
          </v-col>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/heritage/bespokemob.jpg"></v-img>
            </div>
            <nuxt-link style="text-decoration: none" to="/besher"
              ><v-btn class="one1">Read More</v-btn></nuxt-link
            >
            <span class="title4">Bespoke Heritage</span>
          </v-col>
        </v-row>
        <v-row no-gutters>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/kitchen/bespokedesk.jpg"></v-img>
            </div>
            <nuxt-link style="text-decoration: none" to="/beskit">
              <v-btn class="one1">Read More</v-btn></nuxt-link
            >
            <span class="title4">Bespoke Kitchen</span>
          </v-col>
          <v-col cols="12" md="6">
            <div class="inner">
              <v-img class="img" src="/bathroom/bespokemob.jpg"></v-img>
            </div>
            <nuxt-link style="text-decoration: none" to="/besbat">
              <v-btn class="one1">Read More</v-btn></nuxt-link
            >
            <span class="title4">Bespoke Bathroom</span>
          </v-col>
        </v-row>
      </v-row>
    </div>
    <v-divider dark color="orange"></v-divider>
  </div>
</template>

<script>
export default {}
</script>

<style>
.two {
  position: relative;
  left: 35%;
  bottom: 300px;
}

.inner {
  overflow: hidden;
  height: 100%;
  width: 100%;
}
.img {
  transition: all 1.5s ease;
  height: 100%;
}
.inner:hover .img {
  transform: scale(1.1);
}
.one1 {
  position: relative;
  left: 35%;
  bottom: 200px;
}
.title3 {
  position: relative;
  /* right: 10%; */
  left: 10%;
  bottom: 350px;
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
  right: 7%;
  bottom: 250px;
  font-size: 20px;
  color: black;
  text-shadow: 2px 2px white;
  font-weight: bold;
  background-color: white;

  /* background-image: linear-gradient(orange, orange); */
}
.img1 {
  height: 800px;
}
</style>