<template>
  <div>
    <div v-if="!$vuetify.breakpoint.smAndDown">
      <v-row no-gutters>
        <v-col cols="12" md="6">
          <v-card>
            <div class="inner">
              <v-img class="img" src="/services/first.jpeg"></v-img>
            </div>

            <v-btn class="one"> Read More </v-btn>
            <span class="title">Bespoke Developments</span>
          </v-card>
        </v-col>
        <v-col cols="12" md="6">
          <v-card>
            <div class="inner">
              <v-img class="img" src="/services/first.jpeg"></v-img>
            </div>
            <v-btn class="one">Read More</v-btn>
          </v-card>
        </v-col>

        <v-col cols="12" md="6">
          <v-card>
            <div class="inner">
              <v-img class="img" src="/services/first.jpeg"></v-img>
            </div>
            <v-btn class="one">Read More</v-btn>
          </v-card>
        </v-col>
        <v-col cols="12" md="6">
          <v-card>
            <div class="inner">
              <v-img class="img" src="/services/first.jpeg"></v-img>
            </div>
            <v-btn class="one">Read More</v-btn>
          </v-card>
        </v-col>
      </v-row>
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <v-row no-gutters>
        <v-col cols="12" md="6">
          <v-card>
            <div class="inner">
              <v-img class="img" src="/services/first.jpeg"></v-img>
            </div>

            <v-btn class="one1">Read More</v-btn>
          </v-card>
        </v-col>
        <v-col cols="12" md="6">
          <v-card>
            <div class="inner">
              <v-img class="img" src="/services/first.jpeg"></v-img>
            </div>
            <v-btn class="one1">Read More</v-btn>
          </v-card>
        </v-col>

        <v-col cols="12" md="6">
          <v-card>
            <div class="inner">
              <v-img class="img" src="/services/first.jpeg"></v-img>
            </div>
            <v-btn class="one1">Read More</v-btn>
          </v-card>
        </v-col>
        <v-col cols="12" md="6">
          <v-card style="color: white">
            <div class="inner">
              <v-img class="img" src="/services/first.jpeg"></v-img>
            </div>
            <v-btn class="one1"> Read More</v-btn>
          </v-card>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.one {
  position: relative;
  left: 40%;
  bottom: 300px;
  /* background-image: linear-gradient(orange, orange); */
}
.title {
  position: relative;
  left: 10%;
  bottom: 350px;
  font-size: 25px;
  color: orange;

  /* background-image: linear-gradient(orange, orange); */
}

.inner {
  overflow: hidden;
}
.img {
  transition: all 1.5s ease;
}
.inner:hover .img {
  transform: scale(1.1);
}
.one1 {
  position: relative;
  left: 35%;
  bottom: 200px;
}
</style>