<template>
  <section id="ourheros" class="bg-b-greybg py-10 md:py-24">
    <h2 class="lg:text-5xl text-3xl font-light px-3 text-center">
      Our Heros <span class="font-bold">SPEAK!</span>
    </h2>
    <p class="text-center mt-4 mb-8 px-3">
      We have been working with clients around the world
    </p>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 w-10/12 grid-flow-row-dense mx-auto place-items-center">
      <OurHero
        title="Efficient Collaborating"
        brief="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Auctor neque
            sed imperdiet nibh lectus feugiat nunc sem."
        img="client2.png"
      />
      <OurHero
        title="Intuitive Design"
        brief="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Auctor neque
            sed imperdiet nibh lectus feugiat nunc sem."
        img="client2.png"
      />
      <OurHero
        title="Mindblowing Service"
        brief="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Auctor neque
            sed imperdiet nibh lectus feugiat nunc sem."
        img="client2.png"
      />
    </div>
  </section>
</template>

<script lang="ts">
import Vue from 'vue'
import OurHero from './OurHero.vue'

export default Vue.extend({
  components: {
    OurHero,
  },
})
</script>

<style scoped></style>
