<template>
  <div class="PressDesignPage">
    <Nav />
    <Header />
    <br>
    <div class="top">
      <Design />
      <Press />
    </div>
    <div class="bottom">
      <Filetypes />
      <Software />
    </div>
    <Footer />
  </div>
</template>

<script>
import Nav from '~/components/Nav.vue'
import Footer from '~/components/Footer.vue'
import Filetypes from '~/components/Pre-Press_Design/Accepted_Filetypes.vue'
import Press from '~/components/Pre-Press_Design/Pre-Press.vue'
import Design from '~/components/Pre-Press_Design/Design.vue'
import Software from '~/components/Pre-Press_Design/Accepted_Software.vue'
import Header from '~/components/Pre-Press_Design/Pre-Press_Design.vue'

export default {
  components: {
    Nav,
    Footer,
    Header,
    Press,
    Design,
    Software,
    Filetypes,
  }
}
</script>

<style>
  .top {
    display: inline;
  }
  .bottom {
    display: inline;
  }
</style>
