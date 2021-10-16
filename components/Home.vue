<template>
  <div>
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <img class="home" src="/home/home.jpg" alt="" />
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <img class="" src="/home/homephone.jpg" alt="" />
    </div>
    <div>
      <br />
      <p>
        Ace Worldwide Limited creates exquisite homes and projects designed to
        enchant and Inspire, methodically approached and completed meticulously
        where every detail has been considered. Our complete offering of
        services enables us to provide our clientele for all of their
        development requirements within one organisation. Our highly
        professional and experienced teams work seamlessly together to produce
        our uncompromising quality and exacting standards.
      </p>
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
</style>