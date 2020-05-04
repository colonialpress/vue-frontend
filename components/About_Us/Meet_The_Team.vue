<template>
  <div class="MeetTheTeam">
    <div class="hero">
      <h1>Meet The Team</h1>
      <br>
      <p>These dedicated individuals keep the wheel turning!</p>
      <br>
      <div class="container">
        <div class="card">
          <!-- <img src="../../assets/placeholder.jpg"> -->
          <span class="dot"></span>
          <h2>Chris Dry</h2>
        </div>
        <div class="card">
          <!-- <img src="../../assets/placeholder.jpg"> -->
          <span class="dot"></span>
          <h2>Stephanie Dry</h2>
        </div>
        <div class="card">
          <!-- <img src="../../assets/placeholder.jpg"> -->
          <span class="dot"></span>
          <h2>Glenn "Butch" Dry</h2>
        </div>
        <div class="card">
          <!-- <img src="../../assets/placeholder.jpg"> -->
          <span class="dot"></span>
          <h2>Judy Lucas</h2>
        </div>
        <div class="card">
          <!-- <img src="../../assets/placeholder.jpg"> -->
          <span class="dot"></span>
          <h2>Brad</h2>
        </div>
        <div class="card">
          <!-- <img src="../../assets/placeholder.jpg"> -->
          <span class="dot"></span>
          <h2>Van</h2>
        </div>
        <div class="card">
          <!-- <img src="../../assets/placeholder.jpg"> -->
          <span class="dot"></span>
          <h2>Tom</h2>
        </div>
        <div class="card">
          <!-- <img src="../../assets/placeholder.jpg"> -->
          <span class="dot"></span>
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
  .MeetTheTeam .card h2 {
    font-size: 20px;
  }
  .MeetTheTeam .dot {
    height: 250px;
    width: 250px;
    background-color: #285E9C;
    border-radius: 50%;
    display: inline-block;
  }
  .MeetTheTeam .container {
       display: flex;
       align-items: flex-start;
       flex-wrap: wrap;
       justify-content: space-evenly;
       height: 100%;
     }
  .MeetTheTeam .card {
    text-align: center;
    padding: 2% 1%;
  }
</style>
