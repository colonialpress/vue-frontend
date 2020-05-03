<template>
  <div class="Footer">
    <footer>
      <h1>Ready to start printing?</h1>
      <p>
        See what we are capable of by checking out our services or contact us.
      </p>
      <br>
      <div class="buttons">
        <button class="OurServices">
          <nuxt-link class="link" to="/Services">
            <strong>Services &#10148;</strong>
          </nuxt-link>
        </button>
        <button class="ContactUs">
          <nuxt-link class="link" to="/Contact-Us">
            <strong>Contact Us &#10148;</strong>
          </nuxt-link>
        </button>
      </div>
    </footer>
  </div>
</template>
<style>
  .Footer button {
    padding: 15px 10px;
    background-color: #285E9C;
    color: white;
    font-size: 15px;
    border-color: #285E9C;
  }
  .Footer footer {
    padding: 3% 10%;
    background-color: white;
    box-shadow: 10px 10px 10px 10px #D8D8D8;
  }
  .Footer {
    padding: 3% 8%;
  }
  .Footer h1 {
    font-size: 50px;
  }
  .Footer p {
    font-size: 20px;
  }
  .Footer button .link {
    color: white;
    text-decoration: none;
  }
  .Footer button:hover {
    background-color: #701C29;
    border-color: #701C29;
  }
</style>
