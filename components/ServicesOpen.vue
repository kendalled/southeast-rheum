<template>
    <transition
      enter-active-class="transition duration-200 ease-out"
      enter-class="translate-y-1 opacity-0"
      enter-to-class="translate-y-0 opacity-100"
      leave-active-class="transition duration-150 ease-in"
      leave-class="translate-y-0 opacity-100"
      leave-to-class="translate-y-1 opacity-0"
    >
      <div v-if="isOpen" v-click-outside="vcoConfig" class="absolute z-10 w-screen max-w-md px-2 mt-3 -ml-4 transform sm:px-0 lg:ml-0 lg:left-1/2 lg:-translate-x-1/2">
        <div class="overflow-hidden rounded-lg shadow-lg ring-1 ring-black ring-opacity-5">
          <div class="relative grid gap-6 px-5 py-6 bg-white sm:gap-8 sm:p-8">
            <nuxt-link to="/content" title="Personal Injury Law" class="flex items-start p-3 -m-3 rounded-lg hover:bg-gray-50">
              <!-- Heroicon name: outline/chart-bar -->
              <svg
                class="flex-shrink-0 w-6 h-6 text-teal-600"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                aria-hidden="true"
              >
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
              </svg>
              <div class="ml-4">
                <p class="text-base font-medium text-gray-900">
                  Bone & Joint Pain
                </p>
                <p class="mt-1 text-sm text-gray-500">
                  From car accidents to slips &amp; falls, our team is ready for your case.
                </p>
              </div>
            </nuxt-link>
  
            <nuxt-link to="/content" title="Business Law" class="flex items-start p-3 -m-3 rounded-lg hover:bg-gray-50">
              <!-- Heroicon name: outline/cursor-click -->
              <svg
                class="flex-shrink-0 w-6 h-6 text-teal-600"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                aria-hidden="true"
              >
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 15l-2 5L9 9l11 4-5 2zm0 0l5 5M7.188 2.239l.777 2.897M5.136 7.965l-2.898-.777M13.95 4.05l-2.122 2.122m-5.657 5.656l-2.12 2.122" />
              </svg>
              <div class="ml-4">
                <p class="text-base font-medium text-gray-900">
                  Autoimmune Disease
                </p>
                <p class="mt-1 text-sm text-gray-500">
                  Establish a new business, or aqcuire and merge companies with our help.
                </p>
              </div>
            </nuxt-link>
  
            <nuxt-link to="/content" title="Family Law" class="flex items-start p-3 -m-3 rounded-lg hover:bg-gray-50">
              <!-- Heroicon name: outline/shield-check -->
              <svg
                class="flex-shrink-0 w-6 h-6 text-teal-600"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                aria-hidden="true"
              >
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" />
              </svg>
              <div class="ml-4">
                <p class="text-base font-medium text-gray-900">
                  Lupus Treatment
                </p>
                <p class="mt-1 text-sm text-gray-500">
                  As one of the most common autoimmune diseases, we are experts at diagnosing and treating lupus.
                </p>
              </div>
            </nuxt-link>
  
            <a href="#" class="flex items-start p-3 -m-3 rounded-lg hover:bg-gray-50">
              <!-- Heroicon name: outline/refresh -->
              <svg
                class="flex-shrink-0 w-6 h-6 text-teal-600"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                aria-hidden="true"
              >
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 4v5h.582m15.356 2A8.001 8.001 0 004.582 9m0 0H9m11 11v-5h-.581m0 0a8.003 8.003 0 01-15.357-2m15.357 2H15" />
              </svg>
              <div class="ml-4">
                <p class="text-base font-medium text-gray-900">Testimonials</p>
                <p class="mt-1 text-sm text-gray-500">Take a look at our countless positive reviews and successful cases.</p>
              </div>
            </a>
          </div>
          <div class="px-5 py-5 space-y-6 bg-gray-50 sm:flex sm:space-y-0 sm:space-x-10 sm:px-8">
            <div class="flow-root">
              <a href="#" class="flex items-center p-3 -m-3 text-base font-medium text-gray-900 rounded-md hover:bg-gray-100">
                <!-- Heroicon name: outline/play -->
                <svg
                  class="flex-shrink-0 w-6 h-6 text-gray-400"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  aria-hidden="true"
                >
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14.752 11.168l-3.197-2.132A1 1 0 0010 9.87v4.263a1 1 0 001.555.832l3.197-2.132a1 1 0 000-1.664z" />
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
                <span class="ml-3">Watch Demo</span>
              </a>
            </div>
  
            <div class="flow-root">
              <a href="#" class="flex items-center p-3 -m-3 text-base font-medium text-gray-900 rounded-md hover:bg-gray-100">
                <!-- Heroicon name: outline/phone -->
                <svg
                  class="flex-shrink-0 w-6 h-6 text-gray-400"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  aria-hidden="true"
                >
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                </svg>
                <span class="ml-3">Contact Sales</span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </transition>
  </template>
  
  <script>
  import vClickOutside from 'click-outside-vue3'
  export default {
    directives: {
      clickOutside: vClickOutside.directive
    },
    props: {
      open: {
        type: Boolean,
        default: false
      }
    },
    data () {
      return {
        isOpen: false
      }
    },
    computed: {
      vcoConfig () {
        return {
          handler: this.moreOpenMethod,
          events: ['click'],
          // activate / deactivate click-outside directive dynamically
          isActive: this.isOpen
        }
      }
    },
    watch: {
      open (newVal) {
        this.isOpen = newVal
      }
    },
    methods: {
      moreOpenMethod () {
        console.log('Working...services')
        this.isOpen = false
        this.$emit('close')
      }
    }
  }
  </script>
  