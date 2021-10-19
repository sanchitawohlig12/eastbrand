<template>
  <div style="background-color: black">
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <img class="home" src="/interior/onedesk.jpg" alt="" />
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <img class="" src="/interior/onemob.jpg" alt="" />
    </div>
    <div class="besdev">
      <br />
      <p>
        Ace Worldwide Limited specialise in the creation of exquisite
        super-prime projects, for private clients, commercial clients and
        boutique hoteliers. We offer our extensive experience and unrivalled
        services.
      </p>
      <br />
    </div>
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <img class="home" src="/interior/twodesk.jpg" alt="" />
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <img class="" src="/interior/twomob.jpg" alt="" />
    </div>
    <div class="besdev">
      <br />
      <p>
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
.besdev {
  background-color: black;
  color: orange;
  font-size: 20px;
  text-align: center;
}
@media (max-width: 991px) {
  .besdev {
    text-align: justify;
    padding-left: 3%;
    padding-right: 3%;
  }
}
</style>