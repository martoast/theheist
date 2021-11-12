<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col">
        <div class="d-flex">
          <div class="flex-grow-1"></div>
          <b-navbar class="nav" toggleable="sm">
            <b-nav-item href="#"
              ><img src="/THE-HEIST_TWITTER-BUTTON.png"
            /></b-nav-item>
            <b-nav-item href="#"
              ><img src="/THE-HEIST_INSTAGRAM-BUTTON.png"
            /></b-nav-item>
            <b-nav-item href="#"
              ><img src="/THE-HEIST_YOUTUBE-BUTTON.png"
            /></b-nav-item>
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
                >Enter Here</b-button
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="bottom-right">
      <img src="/The-Heist-Website_2.0_DESKTOP-Q_11921.png" />
    </div>
    <div class="bottom-left text-white"></div>
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
  font-size: 24px;
}

.card-btn {
  font-family: "Abys";
  font-size: 36px;
}

/* Bottom right text */
.bottom-right {
  position: absolute;
  bottom: 4px;
  right: 16px;
  z-index: 100000;
}

/* Bottom left text */
.bottom-left {
  position: absolute;
  bottom: 1.5rem;
  left: 16px;
  z-index: 100000;
}
.image-size {
  height: calc(100vh - 56px);
}
</style>
<style>
@media (max-width: 375px) {
  body {
    background-image: url("/landingmobile.jpg");
    background-size: cover;
  }
}
@media (min-width: 380px) {
  body {
    background-image: url("/landingmain.jpg");
    background-size: cover;
  }
}
</style>
