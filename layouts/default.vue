<template>
  <div class="app-container">
    <Header />
    <Sidenav />

    <v-main class="app-content">
      <nuxt />
    </v-main>
  </div>
</template>

<script>
import Header from '~/components/Header'
// import Footer from '~/components/Footer'
import Sidenav from '~/components/Sidenav'
export default {
  components: {
    Header,

    // Footer,
    Sidenav,
  },
  computed: {
    isSidebar() {
      return this.$store.getters['nav/toggleSidebar']
    },
  },
}
</script>

<style>
html,
body {
  margin: 0;
  height: 100%;
  width: 100%;
}
.app-container {
  height: 100%;
  /* overflow-x: hidden; */
  position: relative;
  display: grid;
  grid-template: auto 1fr auto / 1fr;
}
.app-content {
  /* min-height: 100vh; */
  min-width: 100%;
  padding: 24px;
  display: grid;
  align-items: center;
  justify-items: center;
  /* overflow-x: hidden; */
}
@media (max-width: 991px) {
  .app-content {
    overflow-x: hidden;
    overflow-y: hidden;
  }
}
</style>