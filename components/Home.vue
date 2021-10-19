<template>
  <div style="background-color: black">
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <v-carousel cycle height="300" hide-delimiters :show-arrows="false">
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
      <v-carousel cycle height="200" hide-delimiters :show-arrows="false">
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
      <h1 style="text-align: center; font-weight: bold; color: orange">Home</h1>
      <br />
      <p
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
      </p>
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
  /* height: 100%;
  width: 100%; */
  width: 100%;
}
.homecontent {
  margin-left: 170px;
  height: 100%;
  width: 75%;
}
@media (max-width: 991px) {
  .homecontent {
    margin-left: 10px;
    width: 90%;
  }
  .para {
    padding: 0 3%;
  }
}
</style>