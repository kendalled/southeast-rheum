<template>
    <!-- TODO: make spacing proper -->
    <div class="sm:rounded-lg overflow-hidden bg-gray-100">
      <div class="relative bg-white max-w-7xl mx-auto my-24">
        <div class="absolute inset-0">
          <div class="absolute inset-y-0 left-0 w-1/2 bg-gray-50"></div>
        </div>
        <div class="relative mx-auto max-w-7xl lg:grid lg:grid-cols-5">
          <!-- TODO: was py-24 -->
          <div class="rounded-l-lg bg-gradient-to-br from-teal-700 to-teal-800 px-6 py-16 lg:col-span-2 lg:px-8 lg:py-20 xl:pr-12">
            <div class="mx-auto max-w-lg">
              <h2 class="text-2xl font-bold tracking-tight text-teal-50 sm:text-3xl">Ready to book an appointment?</h2>
              <p class="mt-6 text-lg leading-8 text-teal-100">Whether you need diagnosis, treatment, liquid IV care, or just a second opinion, we are here to help. Fill out our simple form to get started in no time. We will help you with any questions you may have.</p>
              <dl class="mt-8 text-base text-teal-100">
                <div>
                  <dt class="sr-only">Postal address</dt>
                  <dd>
                    <p>249 Maitland Ave, Suite 3200</p>
                    <p>Altamonte Springs, FL 32701</p>
                  </dd>
                </div>
                <div class="mt-6">
                  <dt class="sr-only">Phone number</dt>
                  <dd class="flex">
                    <svg class="h-6 w-6 flex-shrink-0 text-teal-400" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z" />
                    </svg>
                    <span class="ml-3">+1 (407) 686-1811</span>
                  </dd>
                </div>
                <div class="mt-3">
                  <dt class="sr-only">Email</dt>
                  <dd class="flex">
                    <svg class="h-6 w-6 flex-shrink-0 text-teal-400" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75" />
                    </svg>
                    <span class="ml-3">sersclinic@gmail.com</span>
                  </dd>
                </div>
              </dl>
              <p class="mt-6 text-base text-teal-300">
                Concerned about insurance?
                <nuxt-link to="/" title="Link to home page" class="font-medium text-teal-200 underline">View our FAQ</nuxt-link>.
              </p>
            </div>
            <!-- start google maps embed TODO: fix spacing to be uniform -->
            <div class="h-auto w-auto bg-teal-900 rounded-md">
              <div class="mapouter mt-16 lg:-mb-10 w-full">
                <div class="gmap_canvas w-full">
                  <iframe class="gmap_iframe rounded-md w-full h-96" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.com/maps?width=600&amp;height=400&amp;hl=en&amp;q=249 Maitland Ave 3200, Altamonte Springs, Florida, 32701&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"></iframe>
                </div>
              </div>
            </div>
            <!-- end google maps embed -->
          </div>
          <div class="rounded-lg bg-white px-6 py-16 lg:col-span-3 lg:px-8 lg:py-20 xl:pl-12">
            <div class="mx-auto max-w-lg lg:max-w-none">
              <form name="Pool Table Doctor Request" method="POST" class="px-6 pb-24 pt-20 sm:pb-32 lg:px-8 lg:py-0" netlify>
                <input type="hidden" name="form-name" value="Pool Table Doctor Request" />
                <div class="mx-auto max-w-xl lg:mx-0 lg:max-w-lg">
                  <h3 class="block text-2xl sm:text-3xl text-teal-900 font-bold leading-6 mb-6 sm:mb-8">Schedule an Appointment</h3>
                  <div class="grid grid-cols-1 gap-x-8 gap-y-6 sm:grid-cols-2">
                    <div>
                      <label for="first-name" class="block text-sm font-semibold leading-6 text-gray-900">First name</label>
                      <div class="mt-2.5">
                        <input type="text" name="first-name" id="first-name" autocomplete="given-name" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-teal-600 sm:text-sm sm:leading-6 focus:outline-none">
                      </div>
                    </div>
                    <div>
                      <label for="last-name" class="block text-sm font-semibold leading-6 text-gray-900">Last name</label>
                      <div class="mt-2.5">
                        <input type="text" name="last-name" id="last-name" autocomplete="family-name" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-teal-600 sm:text-sm sm:leading-6 focus:outline-none">
                      </div>
                    </div>
                    <div class="sm:col-span-1">
                      <label for="email" class="block text-sm font-semibold leading-6 text-gray-900">Email</label>
                      <div class="mt-2.5">
                        <input type="email" name="email" id="email" autocomplete="email" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-teal-600 sm:text-sm sm:leading-6 focus:outline-none">
                      </div>
                    </div>
                    <div class="sm:col-span-1">
                      <label for="phone-number" class="block text-sm font-semibold leading-6 text-gray-900">Phone number</label>
                      <div class="mt-2.5">
                        <input type="tel" name="phone-number" id="phone-number" autocomplete="tel" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-teal-600 sm:text-sm sm:leading-6 focus:outline-none">
                      </div>
                    </div>
                    <Checkboxes class="sm:col-span-2" />
                    <div class="sm:col-span-1">
                      <label for="postal-code" class="block text-sm font-semibold leading-6 text-gray-900">ZIP Code</label>
                      <div class="mt-2.5">
                        <input type="text" name="postal-code" id="postal-code" autocomplete="postal-code" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-teal-600 sm:text-sm sm:leading-6 focus:outline-none">
                      </div>
                    </div>
                    <div class="sm:col-span-1">
                      <label for="zip-code-destination" class="block text-sm font-semibold leading-6 text-gray-900">Insurance Provider</label>
                      <div class="mt-2.5">
                        <input type="text" name="zip-code-destination" id="zip-code-destination" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-teal-600 sm:text-sm sm:leading-6 focus:outline-none">
                      </div>
                    </div>
                    <div class="sm:col-span-2">
                      <label for="message" class="block text-sm font-semibold leading-6 text-gray-900">Message</label>
                      <div class="mt-2.5">
                        <textarea name="message" id="message" rows="4" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-teal-600 sm:text-sm sm:leading-6 focus:outline-none"></textarea>
                      </div>
                    </div>
                  </div>
                  <div class="mt-8 flex justify-end">
                    <button type="submit" class="rounded-md bg-teal-600 px-3.5 py-2.5 text-center text-sm font-semibold text-white shadow-sm hover:bg-teal-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-teal-600">Send message</button>
                  </div>
                </div>
            </form>
            </div>
          </div>
        </div>
      </div>
    </div>
    
    </template>    

<style scoped>
.mapouter {
  position: relative;
  text-align: right;
  height: 400px;
}

.gmap_canvas {
  overflow: hidden;
  background: none !important;
  height: 400px;
}

.gmap_iframe {
  height: 400px !important;
}
</style>    