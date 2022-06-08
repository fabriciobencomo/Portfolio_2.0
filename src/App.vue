<template>
  <Header />
  <Hero />
  <About />
  <Project />
</template>

<script>
import About from './components/About'
import Header from './components/Header.vue'
import Hero from './components/Hero'
import Project from './components/Project'

export default {
  name: 'App',
  components: {
    Header,
    Hero,
    About,
    Project
  }
}
</script>

<style>

</style>
