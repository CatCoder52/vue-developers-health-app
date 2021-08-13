<template>
  <div class="flex-col flex md:flex-row justify-center items-center tex-center mt-8">
    <img
      class="order-1 w-3/12"
      :class="align==='icon-left'? 'md:order-1' :'md:order-2' "
      :src="img"
      alt="icon"
    />
    <div class="w-5/6 md:w-2/4 order-2" :class="align==='icon-right'? 'md:order-1':'md:order-2'">
      <h3 class="font-bold text-lg">
        {{ title }}
      </h3>
      <p class="mt-2">{{ brief }}</p>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  props: {
    img: {
      type: String,
      required: true,
      default: 'feature-m1.svg',
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
    order: {
      type: String,
      default: 'order-1',
    },
  },
  data() {
    return {
      align: this.order,
    }
  },

})
</script>

<style scoped></style>
