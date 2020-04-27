<template>
  <div class="landingImage">
    <img src="../assets/landing-photo.png">
    <p class="moto">
      <strong>Yesteryear's service with tomorrow's technology.</strong>
    </p>
  </div>
</template>
<style>
  .landingImage img {
    width: 100%;
    height: 100%;
  }
  .landingImage {
    position: relative;
    text-align: center;
    color: white;
  }
  .landingImage .moto {
    position: absolute;
    top: 50%;
    left: 20%;
    transform: translate(-50%, -50%);
    font-size: 50px;
    width: 25%;
    text-align: left;
  }
</style>
