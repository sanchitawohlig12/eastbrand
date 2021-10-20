<template>
  <div style="background-color: black">
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <img class="home1" src="/kitchen/onedesk.jpg" alt="" />
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <img class="home1" src="/kitchen/onemob.jpg" alt="" />
    </div>
    <div class="beskit">
      <br />
      <p class="">
        Ace Worldwide Limited specialise in the creation of exquisite
        super-prime projects, for private clients, commercial clients and
        boutique hoteliers. We offer our extensive experience and unrivalled
        services.
      </p>
      <br />
    </div>
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <img class="home1" src="/kitchen/twodesk.jpg" alt="" />
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <img class="home1" src="/kitchen/twomob.jpg" alt="" />
    </div>

    <div class="beskit">
      <br />
      <p class="">
        We provide for the Luxury development sector, and due to our extensive
        and diverse offering of services we are able to assist with all of our
        clients requirements all within one organisation. This in turn enables
        ourselves to provide our clients with one of the most precious
        commodities – Time.
      </p>
      <br />
    </div>
    <br />
    <v-divider color="orange"></v-divider><br />
  </div>
</template>

<script>
export default {}
</script>

<style>
.beskit {
  height: 40%;
  width: 60%;
  background-color: black;
  color: orange;
  font-size: 20px;
  margin-left: 20%;
  text-align: center;
}
@media (max-width: 991px) {
  .beskit {
    height: 40%;
    width: 90%;
    background-color: black;
    color: orange;
    font-size: 20px;
    margin-left: 5%;
  }
}
@media (max-width: 991px) {
  .beskit {
    text-align: justify;
    padding-left: 3%;
    padding-right: 3%;
  }
}
@media (max-width: 320px) {
  .beskit {
    margin-left: 5%;
  }
}
</style>