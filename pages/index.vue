<template>
  <main>
    <Navbar />
    <Header />
    <Stats />
    <Feature />
    <Approach />
    <Services />
    <DiscoverUs />
    <Career />
    <LogoClouds />
    <Testimonials />
    <OurHeros />
    <Contact />
    <Footer />
  </main>
</template>

<script lang="ts">
import Navbar from '../components/Home/Navbar.vue'
import Header from '../components/Home/Header.vue'
import Stats from '../components/Home/Stats.vue'
import Feature from '../components/Home/Feature.vue'
import Approach from '../components/Home/Approach.vue'
import Services from '../components/Home/Services.vue'
import DiscoverUs from '../components/Home/DiscoverUs.vue'
import Career from '../components/Home/Career.vue'
import LogoClouds from '../components/Home/LogoClouds.vue'
import Testimonials from '../components/Home/Testimonials.vue'
import OurHeros from '../components/Home/OurHeros.vue'
import Contact from '../components/Home/Contact.vue'
import Footer from '../components/Home/Footer.vue'
export default {
  components: {
    Navbar,
    Header,
    Stats,
    Feature,
    Approach,
    Services,
    DiscoverUs,
    Career,
    LogoClouds,
    Testimonials,
    OurHeros,
    Contact,
    Footer
  },
}
</script>

<style></style>
