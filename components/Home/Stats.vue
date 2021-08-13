<template>
  <section
   id='Stats'
    class="bg-b-purple py-32 px-42 text-white -mt-20 relative overflow-hidden z-50"
    style="clip-path: polygon(0px 13%, 100% 0px, 100% 100%, 0px 96%)"
  >
    <div class="text-center pt-16">
      <h2 class="lg:text-5xl text-3xl font-light px-3">
        What we <span class="font-bold">believe</span> in
      </h2>
      <p class="text-center mt-4 mb-20 px-3">
        Lorem ipsum is common placeholder text used to demonstrate the graphic
        elements of a <br />
        document or visual presentation.
      </p>
      <div class="grid grid-cols-3 gap-16 my-o mx-auto w-4/6">
        <stats-user></stats-user>
        <stats-user></stats-user>
        <stats-user></stats-user>
        <stats-user></stats-user>
        <stats-user></stats-user>
        <stats-user></stats-user>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import Vue from 'vue'
import StatsUser from './StatsUser.vue'

export default Vue.extend({
  components: {
    StatsUser,
  },
})
</script>

<style scoped></style>
