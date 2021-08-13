<template>
  <section id="discoverus" class="flex flex-wrap md:grid grid-cols-2 py-24">
    <div class="flex flex-col">
      <div class="ml-4 sm:ml-8 md:ml-20 lg:ml-40 px-3">
        <h2 class="font-light lg:text-5xl text-3xl text-t-purplee">
          <span class="lg:text-5xl text-3xl font-bold"
            >Discover <br />
            You are</span
          >
          HERO
        </h2>
        <p class="mt-6">
          Lorem ipsum is common placeholder text used to <br />
          demonstrate the graphic elements of a document or or visual
          presentation.
        </p>
      </div>
      <img src="feature-h-human.svg" alt="human" class="w-4/6 h-4/6 md:transform md:translate-y-60 md:-translate-x-10 xl:translate-y-72"/>
    </div>
    <div
      class="
        grid
        gap-16
        grid-cols-2 grid-flow-row-dense
        mx-4
        sm:mr-8
        md:mr-20
        lg:mr-40
        mt-14
        md:mt-0
      "
    >
      <!-- items -->
      <DiscoverItem
        img="feature-h-icon.svg"
        title="Health"
        brief="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed erat nibh
      tristique ipsum."
      />
      <DiscoverItem
        img="feature-h-icon.svg"
        title="Health"
        brief="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed erat nibh
      tristique ipsum."
      />
      <DiscoverItem
        img="feature-h-icon.svg"
        title="Health"
        brief="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed erat nibh
      tristique ipsum."
      />
      <DiscoverItem
        img="feature-h-icon.svg"
        title="Health"
        brief="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed erat nibh
      tristique ipsum."
      />
      <DiscoverItem
        img="feature-h-icon.svg"
        title="Health"
        brief="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed erat nibh
      tristique ipsum."
      />
      <DiscoverItem
        img="feature-h-icon.svg"
        title="Health"
        brief="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed erat nibh
      tristique ipsum."
      />
      <!-- items -->
    </div>
  </section>
</template>

<script lang="ts">
import Vue from 'vue'
import DiscoverItem from './DiscoverItem.vue'

export default Vue.extend({
  components: {
    DiscoverItem,
  },
})
</script>

<style scoped></style>
