<template>
  <Header />
  <Hero />
  <About />
  <Project />
  <Contact />
</template>

<script>
import About from './components/About'
import Contact from './components/Contact'
import Header from './components/Header.vue'
import Hero from './components/Hero'
import Project from './components/Project'


export default {
  name: 'App',
  components: {
    Header,
    Hero,
    About,
    Project,
    Contact
  }
}
</script>

<style>

</style>
