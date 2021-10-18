<template>
  <div style="background-color: black">
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <v-carousel cycle>
        <v-carousel-item>
          <img class="home" src="/home/main.jpg" alt=""
        /></v-carousel-item>
        <v-carousel-item>
          <img class="home" src="/home/main.jpg" alt=""
        /></v-carousel-item>
      </v-carousel>
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <img class="home" src="/home/homephone.jpg" alt="" />
    </div>
    <div class="homecontent">
      <br />
      <p style="color: orange; text-align: center; font-size: 20px">
        Ace Worldwide Limited creates exquisite homes and projects designed to
        enchant and Inspire, methodically approached and completed meticulously
        where every detail has been considered. Our complete offering of
        services enables us to provide our clientele for all of their
        development requirements within one organisation. Our highly
        professional and experienced teams work seamlessly together to produce
        our uncompromising quality and exacting standards.
      </p>
      <br />
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.home {
  height: 100%;
  width: 100%;
}
.homecontent {
  margin-left: 170px;
  height: 100%;
  width: 75%;
}
@media (max-width: 991px) {
  .homecontent {
    margin-left: 20px;
    width: 90%;
  }
}
</style>