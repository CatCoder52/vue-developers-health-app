<template>
<section>
  <!-- desktop nav -->
    <nav class="hidden sm:hidden md:hidden lg:block">
      <div class="flex justify-between items-center py-3 px-40 ">
        <ul
          class="
            list-none
            grid grid-rows-1 grid-flow-col
            gap-4
            lg:gap-10
           
          "
        >
          <a href="#" class="hover:text-b-purple focus:text-b-purple">
            <li>For Heros</li>
          </a>
          <a href="#" class="hover:text-b-purple focus:text-b-purple">
            <li>For Companies</li>
          </a>
          <a href="#" class="hover:text-b-purple focus:text-b-purple">
            <li>Resources</li>
          </a>
          <a href="#" class="hover:text-b-purple focus:text-b-purple">
            <li>Contact</li>
          </a>
        </ul>
        <div><Logo /></div>
        <div class="flex gap-3">
          <button
            type="button"
            class="
              inline-flex
              items-center
              bg-opacity-30
              px-4
              py-2
              border border-transparent
              text-base
              font-medium
              rounded-md
              text-b-purple
              bg-b-purple
              hover:bg-indigo-200
              focus:outline-none
              focus:ring-2
              focus:ring-offset-2
              focus:ring-indigo-500
            "
          >
            Login
          </button>
          <button
            type="button"
            class="
              inline-flex
              items-center
              px-4
              py-2
              border border-transparent
              text-base
              font-medium
              rounded-md
              shadow-sm
              text-white
              bg-b-purple
              hover:bg-indigo-700
              focus:outline-none
              focus:ring-2
              focus:ring-offset-2
              focus:ring-indigo-500
            "
          >
            Sign up
          </button>
        </div>
      </div>
      <div class="border-b border-gray-100" />
    </nav>
    <!-- mobile nav -->
    <nav class="block md:block lg:hidden sm:block">
      <div class="container py-3 mx-auto">
        <div class="flex justify-between md:px-40 px-20 items-center">

          <!-- left section -->
          <div class="flex justify-between items-center w-full">
            <a
              href="#"
              class="
                text-gray-800 text-xl
                font-bold
                hover:text-gray-700
                md:text-2xl
                
              "
              ><Logo /></a
            >
            <!-- click btn -->
            <div class="lg:hidden block">
              <button
                type="button"
                class="
                  text-gray-500
                  hover:text-gray-600
                  focus:text-gray-600 focus:outline-none
                  mt-2
                "
                @click="isOpen = !isOpen"
              >
                <svg viewBox="0 0 24 24" class="h-6 w-6 fill-current" :class="{ 'block': !isOpen, 'hidden': isOpen }">
                  <path
                    d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
                  ></path>
                </svg>
                <svg
:class="{ 'block': isOpen, 'hidden': !isOpen }"  class="h-6 w-6 fill-current" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
</svg>
              </button>
            </div>
          </div>

      </div>
<!-- right section -->
                      <div
              class="flex-col gap-6 mt-3 md:flex-col md:mt-0  w-3/4 shadow py-8 mx-auto"
              :class="isOpen ? 'flex' : 'hidden'"
            >
              <a href="#" class="text-gray-800 text-sm hover:font-bold ml-32"
                >For Heros</a
              >
              <a href="#" class="text-gray-800 text-sm hover:font-bold ml-32"
                >For Companies</a
              >
              <a href="#" class="text-gray-800 text-sm hover:font-bold ml-32"
                >Resources</a
              >
              <a href="#" class="text-gray-800 text-sm hover:font-bold ml-32"
                >Contact</a
              >
                <!-- btns -->
                <div class="flex gap-3 ml-32">
            <button
              type="button"
              class="
               font-bold
                rounded-md
                text-t-purple
                hover:bg-indigo-700
                focus:outline-none
                focus:ring-2
                focus:ring-offset-2
                focus:ring-indigo-500
              "
            >
              Login
            </button>
            <button
              type="button"
              class="
                font-bold
                rounded-md
                text-t-purple
                hover:bg-indigo-700
                focus:outline-none
                focus:ring-2
                focus:ring-offset-2
                focus:ring-indigo-500
              "
            >
              Sign up
            </button>
                    </div>
            </div>
        </div>
      </div>
      <div class="border-b border-gray-100" />
    </nav>
</section>
</template>

<script lang="ts">
import Vue from 'vue'
import Logo from '../Home/Logo.vue'
export default Vue.extend({
  components : {
  Logo
  },
  data() {
    return { isOpen: false }
  },
})
</script>

<style>

</style>
