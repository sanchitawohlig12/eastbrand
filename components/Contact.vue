<template>
  <div style="background-color: black">
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <img class="home1" src="/contact/desktop.jpg" alt="" />
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <img class="home1" src="/contact/mobile.jpg" alt="" />
    </div>
    <div>
      <br />
      <h1 style="text-align: center; font-weight: bold; color: orange">
        Contact Us
      </h1>
      <br />

      <p
        class="para3"
        style="text-align: center; color: orange; font-size: 20px"
      >
        Should you wish to contact us and discuss an upcoming project then we
        would be delighted to hear from you.
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
.home {
  height: 100%;
  width: 100%;
}
@media (max-width: 991px) {
  .para3 {
    padding-right: 3%;
    padding-left: 3%;
  }
}
</style>