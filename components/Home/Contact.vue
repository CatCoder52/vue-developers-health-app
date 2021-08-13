<template>
  <section class="bg-white" aria-labelledby="contactHeading">
    <div class="h-1/2 bg-warm-gray-50 w-full" aria-hidden="true"></div>
    <div class="mx-auto py-8 lg:py-10 w-5/6">
      <div class="bg-white">
        <div class="grid grid-cols-1 lg:grid-cols-2">
          <!-- Contact information -->
          <div
            class="
              py-10
              bg-gradient-to-b
              from-teal-500
              to-teal-600
            "
          >
            <img src="Telephone.svg" alt="tel" />
            <h3 class="lg:text-5xl text-3xl font-black mt-4">
              Contact <span class="font-light">Us</span>
            </h3>
            <p class="mt-6 text-base text-teal-50 max-w-3xl">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Auctor
              neque sed <br> imperdiet nibh lectus feugiat nunc sem.
            </p>
            <dl class="mt-8 space-y-6">
              <dt><span class="sr-only">Email</span></dt>
              <dd class="flex text-base text-teal-50">
                <img src="Message.svg" alt="svg" />
                <span class="ml-3">hello@devdna.com</span>
              </dd>
              <dt><span class="sr-only">Phone number</span></dt>
              <dd class="flex text-base text-teal-50">
                <img src="Mobile.svg" alt="svg" />
                <span class="ml-3">+91 98765 432107</span>
              </dd>
              <dt><span class="sr-only">Location</span></dt>
              <dd class="flex text-base text-teal-50">
                <img src="Location.svg" alt="svg" />
                <span class="ml-3">DunkerStr. 3, Berlin 10435</span>
              </dd>
            </dl>
          </div>

          <!-- Contact form -->
          <div class="py-10">
            <form class="mt-6 grid grid-cols-1 gap-y-6 sm:gap-x-8">
              <div>
                <label
                  for="first_name"
                  class="block text-sm font-medium text-warm-gray-900"
                  >Your Name</label
                >
                <div class="mt-1">
                  <input
                    id="first_name"
                    type="text"
                    name="first_name"
                    autocomplete="given-name"
                    class="
                      py-3
                      px-4
                      block
                      w-full
                      border border-warm-gray-300
                      text-warm-gray-900
                      focus:ring-teal-500 focus:border-teal-500
                      border-warm-gray-300
                      rounded-md
                    "
                  />
                </div>
              </div>
              <div>
                <label
                  for="email"
                  class="block text-sm font-medium text-warm-gray-900"
                  >Your Email</label
                >
                <div class="mt-1">
                  <input
                    id="email"
                    name="email"
                    type="email"
                    autocomplete="email"
                    class="
                      py-3
                      px-4
                      block
                      w-full
                      text-warm-gray-900
                      focus:ring-teal-500 focus:border-teal-500
                      border border-warm-gray-300
                      rounded-md
                    "
                  />
                </div>
              </div>
              <div></div>

              <div class="">
                <div class="flex justify-between">
                  <label
                    for="message"
                    class="block text-sm font-medium text-warm-gray-900"
                    >Your Message</label
                  >
                </div>
                <div class="mt-1">
                  <textarea
                    id="message"
                    name="message"
                    rows="4"
                    class="
                      py-3
                      px-4
                      block
                      w-full
                      shadow-sm
                      text-warm-gray-900
                      focus:ring-teal-500 focus:border-teal-500
                      border border-warm-gray-300
                      rounded-md
                    "
                    aria-describedby="message-max"
                  ></textarea>
                </div>
              </div>
              <div class="sm:flex sm:justify-end">
                <button
                  type="submit"
                  class="
                    mt-2
                    w-full
                    inline-flex
                    items-center
                    justify-center
                    px-8
                    py-3
                    bg-b-purple
                    border border-transparent
                    rounded-md
                    shadow-sm
                    text-base
                    font-medium
                    text-white
                    bg-teal-500
                    hover:bg-teal-600
                    focus:outline-none
                    focus:ring-2
                    focus:ring-offset-2
                    focus:ring-teal-500
                    sm:w-auto
                  "
                >
                  Submit
                </button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style scoped></style>
