<template>
  <nav>
    <div class="image">
      <img src="../assets/navbar-logo.png">
    </div>
    <div class="navigation">
      <nuxt-link class="link" to="/">
        Home
      </nuxt-link>
      <nuxt-link class="link" to="/Services">
        Services
      </nuxt-link>
      <nuxt-link class="link" to="/Pre-Press-and-Design">
        Pre-Press & Design
      </nuxt-link>
      <nuxt-link class="link" to="/About-Us">
        About Us
      </nuxt-link>
      <nuxt-link class="link" to="/Contact-Us">
        Contact Us
      </nuxt-link>
    </div>
  </nav>
</template>
<style>
  nav {
    height: 50px;
    padding-left: 4%;
    padding-top: 1%;
  }
  .image img {
    float: left;
    height: 65px;
  }
  nav .navigation {
    overflow: hidden;
    background-color: white;
    float: right;
  }
  nav .link:hover {
    border-style: hidden hidden solid hidden;
    border-color: maroon;
    border-width: 2px;
  }
  nav .link:active {
    border-style: hidden hidden solid hidden;
    border-color: maroon;
    border-width: 2px;
  }
  nav .link {
    display: inline-block;
    color: black;
    text-align: center;
    padding: 25px 20px;
    text-decoration: none;
    font-size: 20px;
    border-style: hidden hidden solid hidden;
    border-color: transparent;
    border-width: 2px;
  }
</style>
