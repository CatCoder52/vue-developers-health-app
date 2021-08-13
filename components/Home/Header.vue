<template>
  <header
    class="
      flex flex-wrap
      lg:flex-nowrap
      mt-24
      lg:mt-0
      justify-between
      items-start
      ml-4
      sm:ml-8
      md:ml-20
      lg:ml-40
    "
  >
    <div class="flex flex-col flex-wrap my-auto px-3">
      <h3 class="text-4xl">
        Connecting the <br />
        <span class="text-7xl drop-shadow-sm text-b-fuchsia font-black"
          >Sharpest minds
        </span>
        <br />
        to great oppurtintes, from anywhere and anytime.
      </h3>
      <p class="text-gray-500 mt-8 mb-5">
        Lorem ipsum is common placeholder text used to demonstrate the graphic
        elements of a document or visual presentation.
      </p>
      <div class="flex gap-4">
        <button
          type="button"
          class="
            inline-flex
            items-center
            px-6
            py-3
            border border-transparent
            text-base
            font-medium
            rounded-lg
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
          Join the Squad
        </button>
        <button
          type="button"
          class="
            inline-flex
            items-center
            px-6
            py-3
            border border-transparent
            text-base
            font-medium
            rounded-md
            shadow-lg
            text-white
            bg-b-green
            hover:bg-green-700
            focus:outline-none
            focus:ring-2
            focus:ring-offset-2
            focus:ring-green-500
          "
        >
          Connect to Talent
        </button>
      </div>
    </div>
    <div class="relative">
      <img class="z-10 relative top-0 left-0" src="header-bg.svg" />
      <img class="z-20 absolute top-0 right-12 sm:right-32 w-2/5 h-3/4 " src="header-face.svg" style="margin-top: 16%"/>
    </div>
  </header>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style></style>
