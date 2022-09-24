<template>
  <b-navbar toggleable type="dark" style="background-color: transparent; justify-content: center;">
    <b-navbar-toggle target="navbar-toggle-collapse" style="overflow-anchor: none;
    color: white;
    border-color: white">
    </b-navbar-toggle>

    <b-collapse id="navbar-toggle-collapse" is-nav style="font-family: 'WordOfGod'; font-size: 20px;">
      <b-navbar-nav class="ml-auto mt-2">
        <b-nav-item href="//theheist.world">Home</b-nav-item>
        <b-nav-item href="//mint.theheist.world">Minting</b-nav-item>
        <b-nav-item href="//gallery.theheist.world">Gallery</b-nav-item>
        <b-nav-item href="//dressup.theheist.world">Dressup</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
  
</template>

<style>
  .navbar-dark .navbar-nav .nav-link {
    color: white;
}
.navbar-toggler-icon {
   background-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 30 30'><path stroke='rgba(255, 255, 255, 1)' stroke-linecap='round' stroke-miterlimit='10' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/></svg>") !important;
}
</style>
