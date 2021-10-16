<template>
  <div style="background-color: black">
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <img class="home" src="/contact/desktop.jpg" alt="" />
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <img class="home" src="/contact/mobile.jpg" alt="" />
    </div>
    <div>
      <br />

      <p style="text-align: center; color: white">
        Should you wish to contact us and discuss an upcoming project then we
        would be delighted to hear from you.
      </p>
      <br />
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
</style>