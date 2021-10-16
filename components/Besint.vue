<template>
  <div style="background-color: black">
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <img class="home" src="/interior/onedesk.jpg" alt="" />
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <img class="" src="/interior/onemob.jpg" alt="" />
    </div>
    <div class="besdev" style="text-align: center">
      TFG Bespoke Group of companies specialise in the creation of exquisite
      super-prime projects, for private clients, commercial clients and boutique
      hoteliers. We offer our extensive experience and unrivalled services.
    </div>
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <img class="home" src="/interior/twodesk.jpg" alt="" />
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <img class="" src="/interior/twomob.jpg" alt="" />
    </div>
    <div class="besdev" style="text-align: center">
      We provide for the Luxury development sector, and due to our extensive and
      diverse offering of services we are able to assist with all of our clients
      requirements all within one organisation. This in turn enables ourselves
      to provide our clients with one of the most precious commodities – Time.
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.besdev {
  height: 50%;
  width: 100%;
  background-color: black;
  color: white;
  font-size: 30px;
}
</style>