<template>
    <div class="relative">
      <div class="absolute inset-x-0 bottom-0 h-full bg-gray-100" />
      <div class="w-full mx-0 max-w-none">
        <!-- was rounded-2xl -->
        <div class="relative shadow-xl sm:rounded-none sm:overflow-hidden">
          <div class="absolute inset-0">
            <!-- <picture>
              <source srcset="~/static/hero-1-new.webp" type="image/webp">
              <source srcset="~/static/hero-1-new.jpg" type="image/jpeg">
              <img src="https://images.unsplash.com/photo-1511174511562-5f7f18b874f8?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Example of personal injury" class="object-cover w-full h-full">
            </picture> -->
            <img src="https://images.unsplash.com/photo-1511174511562-5f7f18b874f8?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Example of personal injury" class="object-cover w-full h-full">
            <div class="absolute inset-0 bg-gradient-to-r from-teal-600 to-teal-900 mix-blend-multiply" />
          </div>
          <div class="relative px-4 py-16 mx-auto max-w-7xl sm:px-6 sm:py-24 lg:py-48 lg:px-8">
            <h1 class="text-4xl font-bold text-left sm:tacking-normal sm:text-5xl lg:text-6xl">
              <span class="block text-white">Speak to a doctor</span>
              <span class="block text-teal-200">within one hour.</span>
            </h1>
            <p class="mt-6 mr-auto text-xl text-left text-teal-50 max-w-7xl sm:max-w-2xl">
                Rheumatology care has never been easier. With over thirty years of combined experience, getting your treatment with us ensures you're in the right hands. Contact us or vist a location to get started in minutes.
            </p>
            <div class="max-w-sm mx-auto mt-10 sm:max-w-none sm:flex sm:justify-center">
              <div class="space-y-4 sm:space-y-0 sm:mr-auto sm:inline-grid sm:grid-cols-2 sm:gap-5">
                <nuxt-link to="/contact" title="Contact form" class="flex items-center justify-center px-4 py-3 text-base font-medium text-teal-700 bg-white border border-transparent rounded-md shadow-sm hover:bg-teal-50 sm:px-8">
                  Get started
                </nuxt-link>
                <a href="#" class="flex items-center justify-center px-4 py-3 text-base font-medium text-white bg-teal-500 border border-transparent rounded-md shadow-sm bg-opacity-60 hover:bg-opacity-70 sm:px-8">
                  Learn more
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>

  <script>
  export default {
    name: 'HeroSection'
  }
  </script>
