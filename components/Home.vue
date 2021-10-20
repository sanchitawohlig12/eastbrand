<template>
  <div style="background-color: black">
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <v-carousel cycle height="250px" hide-delimiters :show-arrows="false">
        <v-carousel-item>
          <img class="home1" src="/home/one.jpg" alt=""
        /></v-carousel-item>
        <v-carousel-item>
          <img class="home1" src="/home/two.jpg" alt=""
        /></v-carousel-item>
        <v-carousel-item>
          <img class="home1" src="/home/three.jpg" alt=""
        /></v-carousel-item>
      </v-carousel>
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <v-carousel class="ca" cycle hide-delimiters :show-arrows="false">
        <v-carousel-item>
          <img class="home1" src="/home/one1.jpg" alt=""
        /></v-carousel-item>
        <v-carousel-item>
          <img class="home1" src="/home/two2.jpg" alt=""
        /></v-carousel-item>
        <v-carousel-item>
          <img class="home1" src="/home/three3.jpg" alt=""
        /></v-carousel-item>
      </v-carousel>
    </div>
    <div class="homecontent">
      <br />
      <h1
        style="text-align: center; font-weight: bold; color: orange"
        class="heading"
      >
        Home
      </h1>
      <br />
      <div
        class="para"
        style="color: orange; text-align: justify; font-size: 20px"
      >
        Ace Worldwide Limited creates exquisite homes and projects designed to
        enchant and Inspire, methodically approached and completed meticulously
        where every detail has been considered. Our complete offering of
        services enables us to provide our clientele for all of their
        development requirements within one organisation. Our highly
        professional and experienced teams work seamlessly together to produce
        our uncompromising quality and exacting standards.
      </div>
      <br />
      <br />
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.home1 {
  /* height: 100%; */
  /*width: 100%; */
  width: 100%;
}
.homecontent {
  margin-left: 10%;
  height: 100%;
  width: 75%;
}
@media only screen and (max-width: 768px) {
  .ca {
    height: 400px;
  }
  /* .para {
    margin-top: -250px;
  } */
  .heading {
    margin-top: -250px;
  }
}

@media (max-width: 991px) {
  .homecontent {
    margin-left: 10px;
    width: 90%;
  }

  .para {
    /* padding: 5% 6% 5% 6%; */
    /* border: 2px solid orange; */
    /* word-spacing: 0px; */
    /* width: 50px; */

    padding-left: 2%;
    padding-right: 2%;
  }
}
@media only screen and (min-device-width: 768px) and (max-device-width: 1024px) {
  .heading {
    padding-left: 10%;
    margin-top: 0px;
  }
  .para {
    padding-left: 10%;
  }
}
@media (max-width: 320px) {
  .para {
    padding-right: 18%;
  }
  .heading {
    padding-right: 12%;
  }
  .ca {
    height: 400px;
  }
}
</style>