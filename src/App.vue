<template>
  <Header />
  <Home />
  <About />
</template>

<script>
import Header from './components/Header.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'

export default {
  name: 'App',
  components: {
    Header,
    Home,
    About
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
