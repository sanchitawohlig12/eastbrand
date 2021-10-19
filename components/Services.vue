<template>
  <div style="background-color: black">
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <img class="home1" src="/ourservices/desktop.jpg" alt="" />
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <img class="home1" src="/ourservices/mobile.jpg" alt="" />
    </div>
    <div class="servicecontent">
      <br />
      <h1 style="text-align: center; font-weight: bold; color: orange">
        Our Services
      </h1>
      <br />
      <p
        class="para"
        style="color: orange; text-align: justify; font-size: 20px"
      >
        Ace Worldwide Limited create a truly unique project for our clientele.
        If their has been a place in your life you have visited or moment you
        wish to capture that had significant meaning or impact on you or your
        family's lives, then we would discuss the experience with you to create
        a piece that embraces and reflects on the event and moment captured.
        Once discussed we would provide our professional thoughts and opinion,
        our design team would then prepare drawings to your exact requirements.
        We would demonstrate the various materials that we believe would work
        seamlessly with your vision. Our Unique projects are as individual as
        for whom they are created. These Unique projects are designed and
        created to tell a story in time of ones unforgettable experience or
        moment.
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
.servicecontent {
  margin-left: 170px;
  height: 100%;
  width: 75%;
}
.home1 {
  width: 100%;
}

@media (max-width: 991px) {
  .servicecontent {
    margin-left: 20px;
    width: 85%;
  }
  .para {
  }
}
</style>