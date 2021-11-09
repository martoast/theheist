<template>
  <div>
    <b-navbar
      class="nav"
      toggleable="sm"
      type="light"
      style="background-color: #000000"
    >
      <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>

      <b-navbar-brand class="main-logo text-white">The Heist</b-navbar-brand>

      <!-- <div class="d-flex">
        <b-nav-item href="#">Link</b-nav-item>
        <b-nav-item href="#">Link</b-nav-item>
        <b-nav-item href="#">Link</b-nav-item>
      </div> -->
    </b-navbar>
    <b-img :src="'landing.jpg'" class="landing-img" alt="Responsive image">
    </b-img>
    <b-card style="background-color: #000000" text-variant="white">
      <b-row no-gutters>
        <b-col sm="6">
          <b-card-body>
            <b-card-text class="card-msg">
              A limited Collection of unique NFT tokens, that will allow you to
              dive into a story of coquette mischief and new identities.
            </b-card-text>
          </b-card-body>
          <div style="text-align: center" class="py-3">
            <h3 class="card-btn">Welcome To The Heist</h3>
            <b-button
              pill
              style="background-color: white; color: black; width: 300px"
              to="/landing"
              >Join the Whitelist</b-button
            >
          </div>
        </b-col>
        <b-col sm="6">
          <b-card-img
            :src="'landing2.jpg'"
            alt="Image"
            class="rounded-0"
          ></b-card-img>
        </b-col>
      </b-row>
    </b-card>
  </div>
</template>

<script>
export default {};
</script>
<style scoped>
@font-face {
  font-family: "Abys";
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url("~assets/fonts/abys-regular.otf") format("truetype");
}

@font-face {
  font-family: "komik";
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url("~assets/fonts/komik.ttf") format("truetype");
}

@font-face {
  font-family: "Champange";
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url("~assets/fonts/Champagne.ttf") format("truetype");
}
.landing-img {
  max-width: 100%;

  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;

  /* Needed to position the navbar */
  position: relative;
}
.nav {
  position: absolute;
  z-index: 100000;
}

.main-logo {
  font-family: "komik";
  font-size: 48px;
}

.card-msg {
  font-family: "Champange";
  font-size: 24px;
}

.card-btn {
  font-family: "Abys";
  font-size: 48px;
}
</style>
