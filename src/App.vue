<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Nav from './components/Nav.vue'
import About from './components/About.vue'
import Projects from './components/Projects.vue'
import Feature from './components/Fearure.vue'
import Contact from './components/Contact.vue'
</script>

<template>
  <div>
    <header>
      <Nav />
    </header>
    <section>
      <About/>
    </section>
    <section>
      <Projects/>
    </section>
    <section>
      <Feature/>
    </section>
    <section>
      <Contact/>
    </section>
  </div>
</template>

<style>
@import '@/assets/css/bootstrap.min.css';
@import '@/assets/css/unicons.css';
@import '@/assets/css/owl.carousel.min.css';
@import '@/assets/css/owl.theme.default.min.css';


@import '@/assets/css/tooplate-style.css';

</style>
