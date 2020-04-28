<template>
  <div class="LandingPage">
    <Nav />
    <br>
    <Landing />
    <br>
    <Who />
    <br>
    <Footer />
  </div>
</template>

<script>
import Nav from '~/components/Nav.vue'
import Landing from '~/components/Landing.vue'
import Footer from '~/components/Footer.vue'
import Who from '~/components/About_Us/Who_We_Are.vue'

export default {
  components: {
    Nav,
    Landing,
    Footer,
    Who
  }
}
</script>

<style>
</style>
