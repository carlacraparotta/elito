<template>
  
  <Header />
  <Home />
  <About2 />
  <About />
  <Services />
  <Experience />
  <RecentWork />
  <Testimonial />
  <PricingPlan />
  <Contact />
  <LatestNews />
  <ContactUs />
  <!-- <Carousel /> -->
  <Footer />
  
</template>

<script>

import Header from './components/Header.vue'
import Home from './components/Home.vue'
import About2 from './components/About2.vue'
import About from './components/About.vue'
import Services from './components/Services.vue'
import Experience from './components/Experience.vue'
import RecentWork from './components/RecentWork.vue'
import Testimonial from './components/Testimonial.vue'
import PricingPlan from './components/PricingPlan.vue'
import Contact from './components/Contact.vue'
import LatestNews from './components/LatestNews.vue'
import ContactUs from './components/ContactUs.vue'
// import Carousel from './components/Carousel.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Home,
    About2,
    About,
    Services,
    Experience,
    RecentWork,
    Testimonial,
    PricingPlan,
    Contact,
    LatestNews,
    ContactUs,
    // Carousel,
    Footer
  }
}
</script>

<style>
#app {
  background-color: black;
  color: white;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
