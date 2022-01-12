<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col">
        <div class="d-flex">
          <div class="flex-grow-1"></div>

          <b-navbar class="nav" toggleable="sm">
            <b-nav-item href="//discord.gg/f4PTthWx" class="social-actions"
              ><img src="/OPENSEA.svg"
            /></b-nav-item>
            <b-nav-item
              class="social-actions"
              href="//twitter.com/theheistworld"
              ><img src="/TWITTER.svg"
            /></b-nav-item>
            <b-nav-item
              class="social-actions"
              href="//instagram.com/theheist.world"
              ><img :src="require('~/static/IG.svg')"
            /></b-nav-item>
          </b-navbar>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="offset-md-8">
        <div class="d-flex flex-column justify-content-end">
          <div class="msg-container">
            <p class="main-msg text-white">
              A limited Collection of unique NFT tokens, that will allow you to
              dive into a story of coquette mischief & new identities.
            </p>
            <div class="text-center">
              <h3 class="card-btn text-white">Welcome To The Heist</h3>

              <b-row>
                <b-col>
                  <b-navbar class="nav" style="justify-content: center">
                    <b-nav-item
                      href="//discord.com/invite/theheistworld"
                      class="social-actions-mobile"
                      ><img src="/OPENSEA.svg"
                    /></b-nav-item>

                    <b-nav-item
                      class="social-actions-mobile"
                      href="//instagram.com/theheist.world"
                      ><img src="/IG.svg"
                    /></b-nav-item>
                    <b-nav-item
                      class="social-actions-mobile"
                      href="//twitter.com/theheistworld"
                      ><img src="/TWITTER.svg"
                    /></b-nav-item>
                  </b-navbar>
                </b-col>
              </b-row>

              <b-button pill class="enter-btn border-0"
                >PUBLIC SALE COMING SOON</b-button
              >
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="footer">
      <b-row align-h="between" class="px-4">
        <b-col cols="auto" class="mr-auto p-3">
          <div class="terms" style="text-decoration: underline">
            <nuxt-link to="/terms" class="text-white"
              >THE HEIST TERMS & CONDITIONS</nuxt-link
            >
          </div>
          <div class="terms">2021 THE HEIST ™</div>
        </b-col>
        <b-col cols="auto" class="ml-auto p-3"
          ><img style="height: 36px" src="/Mel-Signature.svg"
        /></b-col>
      </b-row>
    </div>
  </div>
</template>

<script>
export default {
  layout: "main",
};
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
</style>
<style>
/* ----------- iPhone 4 and 4S ----------- */

/* Portrait and Landscape */
@media only screen and (min-device-width: 320px) and (max-device-width: 480px) and (-webkit-min-device-pixel-ratio: 2) {
  body {
    background-image: url("/landingmobile.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;
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

  .social-actions {
    display: none;
  }

  .social-actions-mobile {
    height: 60px;
    width: 60px;
  }

  .msg-container {
    position: absolute;
    padding-left: 3rem;
    padding-right: 3rem;
    padding-top: 0.5rem;
    top: 3.3rem;
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
    font-size: 13px;
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
    width: 135px;
    background-color: rgb(48, 48, 48, 0.5);
    font-family: "Champange";
  }
}

/* ----------- iPhone 5, 5S, 5C and 5SE ----------- */

/* Portrait and Landscape */
@media only screen and (min-device-width: 320px) and (max-device-width: 568px) and (-webkit-min-device-pixel-ratio: 2) {
  body {
    background-image: url("/landingmobile.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;
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

  .social-actions {
    display: none;
  }

  .social-actions-mobile {
    height: 70px;
    width: 70px;
  }

  .msg-container {
    position: absolute;
    padding-left: 3rem;
    padding-right: 3rem;
    padding-top: 0.5rem;
    top: 3.7rem;
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
    font-size: 13px;
  }

  .terms {
    font-family: "Champange";
    font-size: 12px;
  }

  .card-btn {
    font-family: "Abys";
    font-size: 20px;
  }

  .enter-btn {
    width: 125px;
    background-color: rgb(48, 48, 48, 0.5);
    font-family: "Champange";
  }
}

/* ----------- iPhone 6, 6S, 7 and 8 ----------- */

/* Portrait and Landscape */
@media only screen and (min-device-width: 375px) and (max-device-width: 667px) and (-webkit-min-device-pixel-ratio: 2) {
  body {
    background-image: url("/landingmobile.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;
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

  .social-actions {
    display: none;
  }

  .social-actions-mobile {
    height: 70px;
    width: 70px;
  }

  .msg-container {
    position: absolute;
    padding-left: 3rem;
    padding-right: 3rem;
    padding-top: 2rem;
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
    width: 145px;
    background-color: rgb(48, 48, 48, 0.5);
    font-family: "Champange";
  }
}

/* ----------- iPhone 6+, 7+ and 8+ ----------- */

/* Portrait and Landscape */
@media only screen and (min-device-width: 414px) and (max-device-width: 736px) and (-webkit-min-device-pixel-ratio: 3) {
  body {
    background-image: url("/landingmobile.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;
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

  .social-actions {
    display: none;
  }

  .social-actions-mobile {
    height: 70px;
    width: 70px;
  }

  .msg-container {
    position: absolute;
    padding-left: 3rem;
    padding-right: 3rem;
    padding-top: 2rem;
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
    width: 145px;
    background-color: rgb(48, 48, 48, 0.5);
    font-family: "Champange";
  }
}

/* ----------- iPhone X ----------- */

/* Portrait and Landscape */
@media only screen and (min-device-width: 375px) and (max-device-width: 812px) and (-webkit-min-device-pixel-ratio: 3) {
  body {
    background-image: url("/landingmobile.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;
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

  .social-actions {
    display: none;
  }

  .social-actions-mobile {
    height: 70px;
    width: 70px;
  }

  .msg-container {
    position: absolute;
    padding-left: 3rem;
    padding-right: 3rem;
    padding-top: 2rem;
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
    width: 155px;
    background-color: rgb(48, 48, 48, 0.5);
    font-family: "Champange";
  }
}

/* 2778x1284 pixels at 458ppi */
@media only screen and (device-width: 428px) and (device-height: 926px) and (-webkit-device-pixel-ratio: 3) {
  body {
    background-image: url("/landingmobile.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;
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

  .social-actions {
    display: none;
  }

  .social-actions-mobile {
    height: 75px;
    width: 75px;
  }

  .msg-container {
    position: absolute;
    padding-left: 3rem;
    padding-right: 3rem;
    padding-top: 2.8rem;
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
    font-size: 28px;
  }

  .enter-btn {
    width: 155px;
    background-color: rgb(48, 48, 48, 0.5);
    font-family: "Champange";
  }
}

/* ----------- iPad 1, 2, Mini and Air ----------- */

/* Portrait and Landscape */
@media only screen and (min-device-width: 768px) and (max-device-width: 1024px) and (-webkit-min-device-pixel-ratio: 1) {
  body {
    background-image: url("/The-Heist-IPAD.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% calc(100% - 69px);
  }

  .msg-container {
    left: 5rem;
    margin-top: 2rem;
  }

  .social-actions {
    height: 80px;
    width: 80px;
    display: none;
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
    font-size: 22px;
  }

  .terms {
    font-family: "Champange";
    font-size: 16px;
  }

  .card-btn {
    font-family: "Abys";
    font-size: 34px;
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

  .enter-btn {
    width: 300px;
    background-color: rgb(48, 48, 48, 0.5);
    margin-top: 1rem;
    font-family: "Champange";
    font-size: 18px;
  }
}

/* ----------- iPad 3, 4 and Pro 9.7" ----------- */

/* Portrait and Landscape */
@media only screen and (min-device-width: 768px) and (max-device-width: 1024px) and (-webkit-min-device-pixel-ratio: 2) {
  body {
    background-image: url("/The-Heist-IPAD.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% calc(100% - 69px);
  }

  .msg-container {
    position: absolute;
    padding-left: 3rem;
    padding-right: 3rem;
    padding-top: 2rem;
    top: 5rem;
  }

  .social-actions {
    height: 70px;
    width: 70px;
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
    font-size: 38px;
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

  .enter-btn {
    width: 300px;
    background-color: rgb(48, 48, 48, 0.5);
    margin-top: 1rem;
    font-family: "Champange";
    font-size: 18px;
  }
}

/* ----------- iPad Pro 10.5" ----------- */

/* Portrait and Landscape */
@media only screen and (min-device-width: 834px) and (max-device-width: 1112px) and (-webkit-min-device-pixel-ratio: 2) {
  body {
    background-image: url("/The-Heist-IPAD-PRO.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% calc(100% - 69px);
  }

  .msg-container {
    position: absolute;
    padding-left: 3rem;
    padding-right: 3rem;
    padding-top: 2rem;
    top: 5rem;
  }

  .social-actions {
    height: 70px;
    width: 70px;
    display: none;
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
    font-size: 40px;
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

  .enter-btn {
    width: 300px;
    background-color: rgb(48, 48, 48, 0.5);
    margin-top: 1rem;
    font-family: "Champange";
    font-size: 18px;
  }
}

/* ----------- iPad Pro 12.9" ----------- */

/* Portrait and Landscape */
@media only screen and (min-device-width: 1024px) and (max-device-width: 1366px) and (-webkit-min-device-pixel-ratio: 2) {
  body {
    background-image: url("/The-Heist-IPAD-PRO.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% calc(100% - 69px);
  }

  .msg-container {
    position: absolute;
    padding: 4rem;
    bottom: 5rem;
  }

  .social-actions {
    height: 70px;
    width: 70px;
  }

  .social-actions-mobile {
    display: none;
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
    font-size: 40px;
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

  .enter-btn {
    width: 300px;
    background-color: rgb(48, 48, 48, 0.5);
    margin-top: 1rem;
    font-family: "Champange";
    font-size: 18px;
  }
}

/* LAPTOPS */

@media screen and (min-device-width: 1200px) {
  body {
    background-image: url("/landing.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% calc(100% - 69px);
  }

  .msg-container {
    position: absolute;
    padding: 4rem;
    bottom: 5rem;
  }

  .social-actions {
    height: 70px;
    width: 70px;
  }

  .social-actions-mobile {
    display: none;
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
    font-size: 22px;
  }

  .terms {
    font-family: "Champange";
    font-size: 16px;
  }

  .card-btn {
    font-family: "Abys";
    font-size: 34px;
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

  .enter-btn {
    width: 300px;
    background-color: rgb(48, 48, 48, 0.5);
    margin-top: 1rem;
    font-family: "Champange";
    font-size: 18px;
  }
}
</style>
