<template>
  <div id="page-top">
    <Intro/>
    <About/>
    <Portfolio/>
    <Contact/>
    <Footer/>
    <nuxt/>
  </div>
</template>

<script>
import Intro from '~components/Intro.vue'
import About from '~components/About.vue'
import Portfolio from '~components/Portfolio.vue'
import Contact from '~components/Contact.vue'
import Footer from '~components/Footer.vue'

export default {
  components: {
    Intro,
    About,
    Portfolio,
    Contact,
    Footer
  }
}
</script>
<style>

</style>
