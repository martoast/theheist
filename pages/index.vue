<template>
  <div class="container-fluid">
    <!-- <div class="row">
      <div class="col">
        <div class="d-flex">
          <div class="flex-grow-1"></div>
          <b-navbar class="nav" toggleable="sm">
            <b-nav-item href="#"><img src="/image2vector.svg" /></b-nav-item>
            <b-nav-item href="#"><img src="/image2vector.svg" /></b-nav-item>
            <b-nav-item href="#"><img src="/image2vector.svg" /></b-nav-item>
            <b-nav-item href="#"><img src="/image2vector.svg" /></b-nav-item>
          </b-navbar>
        </div>
      </div>
    </div> -->

    <div class="row">
      <div class="offset-md-8">
        <div class="d-flex flex-column justify-content-end">
          <div class="msg-container">
            <p class="main-msg text-white">
              A limited Collection of unique NFT tokens, that will allow you to
              dive into a story of coquette mischief and new identities.
            </p>
            <div class="text-center">
              <h3 class="card-btn text-white">Welcome To The Heist</h3>
              <b-button pill class="enter-btn border-0" to="/landing"
                >Enter Here</b-button
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="footer">
      <div class="container" fluid>
        <b-row align-h="between">
          <b-col cols="auto" class="mr-auto p-3">
            <div class="terms" style="text-decoration: underline">
              ©2021 The Heist LLC
            </div>
            <div class="terms">Terms and conditions</div>
          </b-col>
          <b-col cols="auto" class="ml-auto p-3"
            ><img src="/The-Heist-Website_2.0_DESKTOP-Q_11921.png"
          /></b-col>
        </b-row>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>
<style scoped>
#someDiv {
  line-height: 1.5em;
  height: 3em; /* height is 2x line-height, so two lines will display */
  overflow: hidden; /* prevents extra lines from being visible */
}
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

.footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  background-color: rgb(48, 48, 48);
  color: white;
  text-align: center;
}
</style>
<style>
@media (max-width: 375px) {
  body {
    background-image: url("/landingmobile.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;
  }

  .msg-container {
    position: absolute;
    padding: 3rem;
    top: 4rem;
  }

  /* Bottom right text */
  .bottom-right {
    position: absolute;
    bottom: 0;
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

  .main-msg {
    font-family: "Champange";
    font-size: 14px;
  }

  .terms {
    font-family: "Champange";
    font-size: 12px;
  }

  .card-btn {
    font-family: "Abys";
    font-size: 26px;
  }

  .enter-btn {
    width: 150px;
    background-color: rgb(48, 48, 48, 0.5);
  }
}
@media (min-width: 380px) {
  body {
    background-image: url("/landing.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% calc(100% - 46px);
  }

  .msg-container {
    position: absolute;
    padding: 4rem;
    bottom: 4rem;
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
  .main-msg {
    font-family: "Champange";
    font-size: 24px;
  }

  .terms {
    font-family: "Champange";
    font-size: 16px;
  }

  .card-btn {
    font-family: "Abys";
    font-size: 36px;
  }

  .enter-btn {
    width: 300px;
    background-color: rgb(48, 48, 48, 0.5);
  }
}
</style>
