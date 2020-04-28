<template>
  <div class="LandingPage">
    <Nav />
    <br>
    <Landing />
    <br>
    <Who />
    <br>
    <Team />
    <br>
    <Footer />
  </div>
</template>

<script>
import Nav from '~/components/Nav.vue'
import Landing from '~/components/Landing.vue'
import Footer from '~/components/Footer.vue'
import Who from '~/components/About_Us/Who_We_Are.vue'
import Team from '~/components/About_Us/Meet_The_Team.vue'

export default {
  components: {
    Nav,
    Landing,
    Footer,
    Who,
    Team
  }
}
</script>

<style>
</style>
