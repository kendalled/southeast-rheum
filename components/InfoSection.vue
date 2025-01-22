<template>
    <!-- Feature section with screenshot was:pt instead of py was lg:py-32 -->
    <div class="relative py-16 bg-gray-50 sm:py-24 lg:pb-12">
      <div class="max-w-md px-4 mx-auto text-center sm:px-6 sm:max-w-3xl lg:px-8 lg:max-w-7xl">
        <div>
          <SubText :text="'managing your health, together'" class="text-center" />
          <p class="mt-2 text-3xl font-extrabold tracking-tight text-gray-800 playfair sm:text-4xl">
            No referral? No problem.
          </p>
          <p class="mx-auto mt-5 text-xl text-gray-500 max-w-prose">
            Our rheumatologists possess the expertise and compassion necessary to guide you through your health journey with confidence and care. Our team is here for you, no matter your concerns.
          </p>
        </div>
        <!-- was lg:-mb-80 todo: simplify img classes -->
        <div class="mt-12 lg:grid lg:grid-cols-7">
          <!-- <picture class="w-full h-auto col-span-3 rounded-lg shadow-xl ring-1 ring-black ring-opacity-5">
            <source srcset="~/static/ourTeam.webp" type="image/webp">
            <source srcset="~/static/ourTeam.jpg" type="image/jpeg">
            <img width="521.14" height="348" src="~/static/ourTeam.jpg" alt="Our team of attorneys." class="w-full h-auto col-span-3 rounded-lg shadow-xl ring-1 ring-black ring-opacity-5">
          </picture> -->
          <!-- todo: webp optimize -->
          <img src="/doctor-phone.jpeg" alt="Our team of attorneys." class="w-full h-auto col-span-3 rounded-lg shadow-xl ring-1 ring-black ring-opacity-5">
          <span class="flex flex-col w-full col-span-4 mt-6 text-left lg:mt-0 lg:px-8 lg:justify-center lg:items-center">
            <p class="pb-4 text-lg font-medium text-gray-600 lg:pb-8">
                We provide comprehensive diagnostic evaluations, develop personalized treatment plans, and work closely with you to manage your symptoms and improve your quality of life. Whether you're seeking answers or long-term management, we’re committed to supporting you every step of the way. Explore our patients' experiences below.
            </p>
            <div class="pt-6 border-t border-gray-200">
              <blockquote>
                <div>
                  <p class="text-base text-gray-500">
                    &ldquo;I was dealing with chronic joint pain and fatigue. The team at Southeastern Rheumatology Specialists truly listened and crafted a treatment plan that has made a difference in my life. They’re knowledgeable, compassionate, and always available to help.&rdquo;
                  </p>
                </div>
                <footer class="mt-3">
                  <div class="flex items-center space-x-3">
                    <div class="flex-shrink-0">
                      <picture>
                        <source srcset="/customer.webp" type="image/webp">
                        <source srcset="/customer.jpg" type="image/jpeg">
                        <img src="/customer.jpg" alt="Customer portrait" class="w-6 h-6 rounded-full">
                      </picture>
                    </div>
                    <div class="text-base font-medium text-gray-700">
                      John Fitzgerald, Business Owner
                    </div>
                  </div>
                </footer>
              </blockquote>
            </div>
          </span>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'InfoSection'
  }
  </script>
  