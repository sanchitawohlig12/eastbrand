<template>
  <ul class="nav-list">
    <li class="nav-item"><nuxt-link to="/home">Home</nuxt-link></li>
    <li class="nav-item"><nuxt-link to="/services">Our Services</nuxt-link></li>
    <li class="nav-item"><nuxt-link to="/about">About Us</nuxt-link></li>
    <li class="nav-item"><nuxt-link to="/contact">Contact Us</nuxt-link></li>
  </ul>
</template>

<style scoped>
.nav-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.nav-item {
  margin: 0 10px;
  margin-top: 40px;
}

.nav-item a {
  text-decoration: none;
  color: white;
  font-size: 20px;
  padding: 25px;
  /* text-decoration: underline; */
}

.nav-item a:hover,
.nav-item a:active {
  color: orange;
}
a.nuxt-link-active {
  color: orange;
}
/* .nav-item a:visited {
  color: orange;
} */

@media (max-width: 991px) {
  .nav-list {
    display: block;
  }
  .nav-item {
    margin-top: 16px;
    margin-bottom: 16px;
  }
  .nav-item a {
    text-decoration: none;
    color: black;
    font-size: 20px;
    padding: 25px;
    /* text-decoration: underline; */
  }
}

@media (min-width: 991px) {
  .nav-list {
    display: flex;
  }
}
</style>