<template>
  <div class="MeetTheTeam">
    <div class="hero">
      <h1>Meet The Team</h1>
      <br>
      <p>These dedicated individuals keep the wheel turning!</p>
      <br>
      <div class="container">
        <div class="card">
          <img src="../../assets/placeholder.jpg">
          <h2>Chris Dry</h2>
        </div>
        <div class="card">
          <img src="../../assets/placeholder.jpg">
          <h2>Stephanie Dry</h2>
        </div>
        <div class="card">
          <img src="../../assets/placeholder.jpg">
          <h2>Glenn "Butch" Dry</h2>
        </div>
        <div class="card">
          <img src="../../assets/placeholder.jpg">
          <h2>Judy Lucas</h2>
        </div>
        <div class="card">
          <img src="../../assets/placeholder.jpg">
          <h2>Brad</h2>
        </div>
        <div class="card">
          <img src="../../assets/placeholder.jpg">
          <h2>Van</h2>
        </div>
        <div class="card">
          <img src="../../assets/placeholder.jpg">
          <h2>Tom</h2>
        </div>
        <div class="card">
          <img src="../../assets/placeholder.jpg">
          <h2>Duncan</h2>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
  .MeetTheTeam {
    padding: 8% 15%;
  }
  .MeetTheTeam h1 {
    font-size: 65px;
  }
  .MeetTheTeam p {
    font-size: 18px;
  }
  .MeetTheTeam .container {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap-reverse;
    flex-flow: column wrap;
    justify-content: center;
  }
  .MeetTheTeam .card {
    text-align: center;
    flex: 1 1 auto;
  }
</style>
