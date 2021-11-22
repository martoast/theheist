<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="black">
      <b-navbar-brand class="logo" href="#">The Heist</b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item class="social-actions"
            ><img src="/OPENSEA.svg"
          /></b-nav-item>
          <b-nav-item class="social-actions" href="//twitter.com/theheistworld"
            ><img src="/TWITTER.svg"
          /></b-nav-item>
          <b-nav-item class="social-actions">
            <img src="/YOUTUBE.svg" />
          </b-nav-item>
          <b-nav-item
            class="social-actions"
            href="//instagram.com/theheist.world"
            ><img :src="require('~/static/IG.svg')"
          /></b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <div>
      <b-img src="/MINTING-BUTTON (1).jpg" fluid alt="Responsive image"></b-img>
    </div>
    <div>
      <b-img
        src="/The-Heist-Website-SCROLL-SIDE-WAYS-BAR.jpg"
        fluid
        alt="Responsive image"
      ></b-img>
    </div>
    <div>
      <b-img src="/website-banner.jpg" fluid alt="Responsive image"></b-img>
    </div>
    <div class="footer">
      <b-row align-h="between" class="px-4">
        <b-col cols="auto" class="mr-auto p-3">
          <div class="terms" style="text-decoration: underline">
            THE HEIST Terms and conditions
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
  data() {
    return {};
  },
};
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
</style>

<style>
body {
  background-color: black;
}
.footer {
  left: 0;
  bottom: 0;
  width: 100%;
  background-color: rgb(48, 48, 48);
  color: white;
  text-align: center;
}

.logo {
  font-family: "komik";
  font-size: 32px;
}

.terms {
  font-family: "Champange";
  font-size: 12px;
}
.social-actions {
  height: 60px;
  width: 60px;
}
</style>
