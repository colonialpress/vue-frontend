<template>
  <div class="Advertising">
    <h1>Advertising</h1>
    <br>
    <div class="container">
      <p class="item">Pens</p>
      <p class="item">Pencils</p>
      <p class="item">Post-it Notes</p>
      <p class="item">Bags</p>
      <p class="item">Balloons</p>
      <p class="item">Mouse Pads</p>
      <p class="item">Cups/Mugs</p>
      <p class="item">Key Chains</p>
      <p class="item">Bumper Stickers</p>
      <p class="item">Window Clings</p>
      <p class="item">Magnetic Cards/Signs</p>
      <p class="item">Yard Signs</p>
    </div>
  </div>
</template>
<style>
  .Advertising {
    padding: 2% 5%;
  }
  .Advertising .container {
    display: flex;
    align-items: flex-start;
    flex-wrap: wrap;
    justify-content: space-between;
    height: 100%;
  }
  .Advertising .item {
    text-align: left;
    padding-left: 2%;
    padding-right: 2%;
    width: 25%;
    color: #383838;
  }
  .Advertising h1 {
    font-size: 50px;
  }
  .Advertising p {
    font-size: 18px;
  }
</style>
