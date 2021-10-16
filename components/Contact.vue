<template>
  <div>
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <img class="home" src="/contact/desktop.jpg" alt="" />
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <img class="" src="/contact/mobile.jpg" alt="" />
    </div>
    <div>
      <p style="text-align: center">
        Should you wish to contact us and discuss an upcoming project then we
        would be delighted to hear from you.
      </p>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
</style>