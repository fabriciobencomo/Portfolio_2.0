<template>
  <Header />
  <Hero />
  <Project />
</template>

<script>
import Header from './components/Header.vue'
import Hero from './components/Hero'
import Project from './components/Project'

export default {
  name: 'App',
  components: {
    Header,
    Hero,
    Project
  }
}
</script>

<style>

</style>
