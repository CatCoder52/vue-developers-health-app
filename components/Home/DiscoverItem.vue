<template>
  <div class="flex flex-col justify-center items-center">
    <img :src="img" alt="icon" width="60" />
    <h3 class="font-bold mt-6 text-lg">{{ title }}</h3>
    <p class="mt-2 text-center">
      {{ brief }}
    </p>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  props: {
    img: {
      type: String,
      required: true,
      default: 'feature-h-icon.svg',
    },
    title: {
      type: String,
      required: true,
      default: 'Title',
    },
    brief: {
      type: String,
      required: true,
      default: 'Lorem ipsum brief',
    },
  },

})
</script>

<style scoped></style>
