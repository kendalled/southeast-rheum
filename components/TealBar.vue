<template>
  <div class="h-auto bg-teal-900 text-teal-50">
    <div class="flex items-center justify-between w-full px-4 py-2.5 mx-auto max-w-7xl sm:px-6">
      <!-- icons only -->
      <div class="flex items-center ml-1 space-x-4">
        <!-- facebook -->
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="inline-block w-5 h-5 text-teal-100"
          width="44"
          height="44"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path stroke="none" d="M0 0h24v24H0z" fill="none" />
          <path d="M7 10v4h3v7h4v-7h3l1 -4h-4v-2a1 1 0 0 1 1 -1h3v-4h-3a5 5 0 0 0 -5 5v2h-3" />
        </svg>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="inline-block w-5 h-5 text-teal-100"
          width="44"
          height="44"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path stroke="none" d="M0 0h24v24H0z" fill="none" />
          <path d="M22 4.01c-1 .49 -1.98 .689 -3 .99c-1.121 -1.265 -2.783 -1.335 -4.38 -.737s-2.643 2.06 -2.62 3.737v1c-3.245 .083 -6.135 -1.395 -8 -4c0 0 -4.182 7.433 4 11c-1.872 1.247 -3.739 2.088 -6 2c3.308 1.803 6.913 2.423 10.034 1.517c3.58 -1.04 6.522 -3.723 7.651 -7.742a13.84 13.84 0 0 0 .497 -3.753c-.002 -.249 1.51 -2.772 1.818 -4.013z" />
        </svg>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="inline-block w-5 h-5 text-teal-100"
          width="44"
          height="44"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path stroke="none" d="M0 0h24v24H0z" fill="none" />
          <rect x="4" y="4" width="16" height="16" rx="4" />
          <circle cx="12" cy="12" r="3" />
          <line x1="16.5" y1="7.5" x2="16.5" y2="7.501" />
        </svg>
      </div>
      <!-- icons w/ info -->
      <div class="flex items-center space-x-4">
        <!-- phone -->
        <span class="flex items-center space-x-2 group">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="inline-block w-5 h-5 text-teal-100 cursor-pointer group-hover:text-teal-50"
            width="44"
            height="44"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            fill="none"
            stroke-linecap="round"
            stroke-linejoin="round"
            @click.prevent="togglePhone"
          >
            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
            <path d="M5 4h4l2 5l-2.5 1.5a11 11 0 0 0 5 5l1.5 -2.5l5 2v4a2 2 0 0 1 -2 2a16 16 0 0 1 -15 -15a2 2 0 0 1 2 -2" />
          </svg>
          <a class="hidden text-sm text-teal-100 md:inline-block hover:text-teal-50" href="tel:4076861811" target="_blank">407-686-1811</a>
          <a v-show="phoneOpen" class="text-sm text-teal-100 md:hidden hover:text-teal-50" href="tel:4076861811" target="_blank">407-686-1811</a>
        </span>
        <!-- email -->
        <span class="flex items-center space-x-2 group">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="inline-block w-5 h-5 text-teal-100 cursor-pointer group-hover:text-teal-50"
            width="44"
            height="44"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            fill="none"
            stroke-linecap="round"
            stroke-linejoin="round"
            @click.prevent="openEmail"
          >
            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
            <rect x="3" y="5" width="18" height="14" rx="2" />
            <polyline points="3 7 12 13 21 7" />
          </svg>
          <a class="hidden text-sm text-teal-100 md:inline-block hover:text-teal-50" href="mailto:sersclinic@gmail.com" target="_blank">sersclinic@gmail.com</a>
          <a v-show="emailOpen" class="inline-block text-sm text-teal-100 md:hidden hover:text-teal-50" href="mailto:sersclinic@gmail.com" target="_blank">sersclinic@gmail.com</a>
        </span>

        <!-- location -->
        <span class="flex items-center space-x-2 group">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="inline-block w-5 h-5 text-teal-100 cursor-pointer group-hover:text-teal-50"
            width="44"
            height="44"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            fill="none"
            stroke-linecap="round"
            stroke-linejoin="round"
            @click.prevent="openMap"
          >
            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
            <circle cx="12" cy="11" r="3" />
            <path d="M17.657 16.657l-4.243 4.243a2 2 0 0 1 -2.827 0l-4.244 -4.243a8 8 0 1 1 11.314 0z" />
          </svg>
          <a class="hidden text-sm text-teal-100 md:inline-block hover:text-teal-50" href="https://maps.google.com/maps?q=249 Maitland Ave 3200, Altamonte Springs, Florida, 32701" target="_blank">249 Maitland Avenue, Suite 3200</a>
          <a v-show="mapOpen" class="inline-block text-xs text-teal-100 md:hidden hover:text-teal-50" href="https://maps.google.com/maps?q=249 Maitland Ave 3200, Altamonte Springs, Florida, 32701" target="_blank">249 Maitland Avenue, #3200</a>
        </span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'tealBar',
  data () {
    return {
      emailOpen: false,
      mapOpen: false,
      phoneOpen: false
    }
  },
  methods: {
    togglePhone () {
      if (this.emailOpen) {
        this.emailOpen = false
      }
      if (this.mapOpen) {
        this.mapOpen = false
      }
      this.phoneOpen = !this.phoneOpen
    },
    openMap () {
      if (this.emailOpen) {
        this.emailOpen = false
      }
      if (this.phoneOpen) {
        this.phoneOpen = false
      }
      this.mapOpen = !this.mapOpen
    },
    openEmail () {
      if (this.mapOpen) {
        this.mapOpen = false
      }
      if (this.phoneOpen) {
        this.phoneOpen = false
      }
      this.emailOpen = !this.emailOpen
    }
  }
}
</script>
