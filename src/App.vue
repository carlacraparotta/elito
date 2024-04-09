<template>
  <Header />
  <Home />
  <About />
  <Service />
  <RecentWork />
  <Contact />

</template>

<script>
import Header from './components/Header.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Service from './components/Service.vue'
import RecentWork from './components/RecentWork.vue'
import Contact from './components/Contact.vue'

export default {
  name: 'App',
  components: {
    Header,
    Home,
    About,
    Service,
    RecentWork,
    Contact
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
