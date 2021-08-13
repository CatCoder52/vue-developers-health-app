<template>
  <section id="services" class="bg-b-greybg py-24">
    <h2 class="lg:text-5xl text-3xl text-center font-light">
      Our <span class="font-bold text-t-purple">Services</span>
    </h2>
    <p class="text-center mt-4 px-3">
      Lorem ipsum is common placeholder text used to demonstrate the graphic
      elements of a <br />
      document or visual presentation.
    </p>
    <ServiceItem
      img="feature-m1.svg"
      title="Adjusting everything  to the right  proportion"
      brief="Lorem ipsum is common placeholder text used to demonstrate the graphic elements of a document or visual presentation. Lorem ipsum is common placeholder text used to demonstrate the graphic elements of a document or visual presentation."
      order="icon-left"
    />
    <ServiceItem
      img="feature-m2.svg"
      title="Filling the missing part"
      brief="Lorem ipsum is common placeholder text used to demonstrate the graphic elements of a document or visual presentation. Lorem ipsum is common placeholde."
      order="icon-right"
    />
    <ServiceItem
      img="feature-m3.svg"
      title="Adjusting everything  to the right  proportion"
      brief="Lorem ipsum is common placeholder text used to demonstrate the graphic elements of a document or visual presentation. Lorem ipsum is common placeholder text used to demonstrate the graphic elements of a document or visual presentation."
      order="icon-left"
    />
      <div class="-mt-28">
    <div class="flex gap-2 justify-center">
      <button
        type="button"
        class="
          inline-flex
          items-center
          px-6
          py-3
          mt-40 md:mt-32
          border border-transparent
          text-base
          font-medium
          rounded-md
          shadow-lg
          text-white
          bg-b-purple
          hover:bg-indigo-700
          focus:outline-none
          focus:ring-2
          focus:ring-offset-2
          focus:ring-indigo-500
        "
      >
        Join the Squad now!
      </button>
    </div>
  </div>
  </section>
</template>

<script lang="ts">
import Vue from 'vue'
import ServiceItem from './ServiceItem.vue'
export default Vue.extend({
  components: {
    ServiceItem,
  },
})
</script>

<style scoped></style>
