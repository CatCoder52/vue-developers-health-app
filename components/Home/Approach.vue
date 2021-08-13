<template>
  <section  id='approach' class="mb-20">
    <div class="flex justify-between">
      <img class="-mt-80 w-2/12" src="dna.svg" alt="dna" />
      <div
        class="bg-no-repeat bg-contain bg-center w-full pb-48 my-0 mx-auto"
      >
        <h2 class="lg:text-5xl text-3xl text-center font-light lg:mt-20 mt-16 text-t-purple ">
          There's a <span class="font-bold">path</span> to follow
        </h2>
        <p class="text-center mt-4 mb-20 ">
          Lorem ipsum is common placeholder text used to demonstrate the graphic
          elements of a <br />
          document or visual presentation.
        </p>
        <div class="grid grid-cols-1 md:grid-cols-4 gap-4 grid-flow-row place-items-center my-o mx-auto w-4/6">
      <approach-feat
        img="approach1.svg"
        title="Building a second brain"
        brief="Turn your idea from concept to MVP"
      />
      <approach-feat
        img="approach2.svg"
        title="Meta Learning"
        brief="Sketch out the product to align the user needs"
      />
      <approach-feat
        img="approach3.svg"
        title="Health and social tips"
        brief="Convert the designs into a live application"
      />
      <approach-feat
        img="approach4.svg"
        title="Financial freedom"
        brief="Launching the application to the market"
      />
    </div>
      </div>
      <img class="w-1/12 -mt-80" src="dna-2.svg" alt="dna" />
    </div>
    <ApproachCta/>
      <img class="w-1/12 ml-auto mr-12 -mt-16" src="dna-3.svg" alt="dna" />
  </section>
</template>

<script lang="ts">
import Vue from 'vue'
import ApproachFeat from './ApproachFeat.vue'
import ApproachCta from './ApproachCta.vue'
export default Vue.extend({
  components: {
    ApproachFeat,
    ApproachCta
  },

})
</script>

<style scoped></style>
