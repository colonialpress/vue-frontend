<template>
  <div class="ServicesPage">
    <Nav />
    <br>
    <Header />
    <Printing />
    <Print />
    <br>
    <Advertising />
    <br>
    <Finishing />
    <br>
    <Footer />
  </div>
</template>

<script>
import Nav from '~/components/Nav.vue'
import Header from '~/components/Services/Our_Services.vue'
import Footer from '~/components/Footer.vue'
import Print from '~/components/Services/Print.vue'
import Printing from '~/components/Services/Printing.vue'
import Advertising from '~/components/Services/Advertising.vue'
import Finishing from '~/components/Services/Finishing.vue'

export default {
  components: {
    Nav,
    Header,
    Footer,
    Print,
    Printing,
    Advertising,
    Finishing
  }
}
</script>

<style>
</style>
