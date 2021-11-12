<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col">
        <div class="d-flex">
          <div class="flex-grow-1"></div>
          <b-navbar class="nav" toggleable="sm">
            <b-nav-item href="#">Link</b-nav-item>
            <b-nav-item href="#">Link</b-nav-item>
            <b-nav-item href="#">Link</b-nav-item>
          </b-navbar>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="col- offset-md-8">
        <div class="d-flex flex-column justify-content-end image-size">
          <div class="p-4 mb-5">
            <p class="main-msg">
              A limited Collection of unique NFT tokens, that will allow you to
              dive into a story of coquette mischief and new identities.
            </p>
            <div class="py-3">
              <h3 class="card-btn text-white">Welcome To The Heist</h3>
              <b-button
                pill
                style="background-color: white; color: black; width: 300px"
                to="/landing"
                >Join the Whitelist</b-button
              >
            </div>
          </div>
        </div>
      </div>
    </div>
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
  z-index: 100000;
}

.main-logo {
  font-family: "komik";
  font-size: 48px;
}

.main-msg {
  font-family: "Champange";
  font-size: 22px;
}

.card-btn {
  font-family: "Abys";
  font-size: 36px;
}

/* Bottom right text */
.bottom-right {
  position: absolute;
  bottom: 8px;
  right: 16px;
}
.image-size {
  height: calc(100vh - 56px);
}
</style>
<style>
body {
  background-image: url("/landing.jpg");
  background-size: cover;
}
</style>
