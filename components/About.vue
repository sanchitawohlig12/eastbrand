<template>
  <div style="background-color: black">
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <img class="home1" src="/about/desktop.jpg" alt="" />
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <img class="home1" src="/about/mobile.jpg" alt="" />
    </div>
    <div style="background-color: black">
      <br />
      <h1 style="text-align: center; font-weight: bold; color: orange">
        Our Company
      </h1>

      <!-- <br /> -->
      <!-- <v-divider color="orange"></v-divider> -->

      <br />
      <div class="aboutcontent">
        <p class="about">
          Ace Worldwide Limited was founded to provide a superior-prime
          luxurious service for our clientele, and to create exquisite,
          desirable and exceptional homes. The comprehensive luxury company
          cater for the majority of the development sector. Our vision was to
          create a vast unparalleled monopoly of luxurious companies, so as we
          could provide a full suite of development services to cater for all of
          our clienteles pacific needs and requirements all within one
          organisation. We provide for a complete and diverse range of projects
          including in Contemporary, Modern, and Traditional homes. We combine
          state of the art technology, married with the most beautiful hand
          crafted materials. Creating developments that are individual,
          exclusive and truly magnificent. We offer a development management
          turnkey service from concept through to completion. Our passionate,
          dedicated and highly talented professional teams of Crafts people,
          designers, architects and surveyors work seamlessly together to create
          our uncompromising signature finish. We instruct perfection on all
          levels of the process, to insure unequivocally the finest results. The
          consistent immeasurable passion we have in every project and aspect
          that we undertake, is always combined with a true obsession for
          perfection. We uphold a methodical and meticulous approach to every
          aspect and detail of the process, Insuring every element is to our
          exacting standards. Our values and principles that the company began
          with and define us, will always remain unchanging. Over the years we
          have built strong and trusted relationships with our clientele and are
          constantly appreciative and flattered as to the regularity of which
          they return and recommend our services. As the majority of our work is
          from recommendation, this to ourselves is a true testament as to the
          relationships we hold with our clients and their assurance and
          confidence in our aptitude to deliver.
        </p>

        <br />
      </div>

      <br />
      <br />
      <v-divider color="orange"></v-divider>
      <br />
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.about {
  display: flex;
  color: orange;
  text-align: center;
  font-size: 20px;
  /* justify-content: center; */
}
.aboutcontent {
  display: flex;
  margin-left: 140px;
  height: 100%;
  width: 80%;
  justify-content: center;
}
@media (max-width: 991px) {
  .aboutcontent {
    margin-left: 20px;
    /* margin-right: 40px; */
    width: 90%;
  }
}
@media only screen and (min-device-width: 768px) and (max-device-width: 1024px) {
  .aboutcontent {
    margin-left: 40px;

    width: 90%;
  }
}
</style>