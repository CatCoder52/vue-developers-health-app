<template>
  <blockquote class="flex flex-col items-center justify-items-center">
    <div
      class="text-center p-8 rounded border border-gray-100"
      style="box-shadow: 0px 30px 40px rgba(212, 217, 232, 0.2)"
    >
      <h3 class="font-bold text-xl">{{ title }}</h3>
      <p class="mt-2">
        {{ brief }}
      </p>
    </div>
    <div
      class="w-5 h-4 bg-white -mt-1"
      style="clip-path: polygon(53% 100%, 0 0, 100% 0)"
    ></div>
    <footer class="mt-2 text-center">
      <img :src="img" alt="client" class="inline mb-2" />
      <div class="clien text-t-purple">
        <p class="text-base font-bold">Jene Cooper</p>
        <p class="text-base">CEO at ABC Corporation</p>
      </div>
    </footer>
  </blockquote>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  props: {
    img: {
      type: String,
      required: true,
      default: 'client2.png',
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
