<template>
  <div class="flex flex-col text-left">
    <img :src="img" alt='icon' />
    <h3 class="font-bold mt-2">{{ title }}</h3>
    <p>{{ brief }}</p>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  props: {
    img: {
      type: String,
      required: true,
      default: 'approach3',
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
  watch: {
    img(val) {
      // eslint-disable-next-line vue/no-mutating-props
      this.img = val
    },
  },
})
</script>

<style scoped></style>
