<template>
  <div>
    <b-navbar toggleable="sm" type="dark" style="background-color: tranparent">
      <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>
      <b-collapse id="nav-text-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item class="item text-white" href="/">Home</b-nav-item>
          <b-nav-item class="item text-white" href="/about-us"
            >About us</b-nav-item
          >
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <Nuxt />
  </div>
</template>
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

.item {
  font-family: "komik";
  font-size: 16px;
}
</style>
