<template>
    <div class="bg-white">
  <header class="relative bg-slate-800 pb-36">
    <div class="absolute inset-0">
      <img class="size-full object-cover" src="https://images.unsplash.com/photo-1525130413817-d45c1d127c42?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1920&q=60&&sat=-100" alt="">
      <div class="absolute inset-0 bg-slate-800 mix-blend-multiply" aria-hidden="true"></div>
    </div>
    <div class="relative z-10">
      <nav class="relative mx-auto flex max-w-7xl items-center justify-between px-6 pb-2 pt-6 lg:px-8" aria-label="Global">
        <div class="flex flex-1 items-center">
          <div class="flex w-full items-center justify-between lg:w-auto">
            <a href="#">
              <span class="sr-only">Your Company</span>
              <img class="h-8 w-auto sm:h-10" src="https://tailwindui.com/plus/img/logos/mark.svg?color=teal&shade=500" alt="">
            </a>
            <div class="-mr-2 flex items-center lg:hidden">
              <button type="button" class="focus-ring-inset relative inline-flex items-center justify-center rounded-md p-2 text-white hover:bg-slate-900 focus:outline-none focus:ring-2 focus:ring-white" aria-expanded="false">
                <span class="absolute -inset-0.5"></span>
                <span class="sr-only">Open main menu</span>
                <svg class="size-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true" data-slot="icon">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                </svg>
              </button>
            </div>
          </div>
          <div class="hidden space-x-10 lg:ml-10 lg:flex">
            <a href="#" class="text-base font-medium text-white hover:text-teal-100">Changelog</a>
            <a href="#" class="text-base font-medium text-white hover:text-teal-100">About</a>
            <a href="#" class="text-base font-medium text-white hover:text-teal-100">Partners</a>
            <a href="#" class="text-base font-medium text-white hover:text-teal-100">News</a>
          </div>
        </div>
        <div class="hidden lg:flex lg:items-center lg:space-x-6">
          <a href="#" class="rounded-md border border-transparent bg-teal-500 px-6 py-2 text-base font-medium text-white shadow-md hover:bg-teal-600">Login</a>
        </div>
      </nav>

      <!--
        Mobile menu, show/hide based on menu open state.

        Entering: "duration-150 ease-out"
          From: "opacity-0 scale-95"
          To: "opacity-100 scale-100"
        Leaving: "duration-100 ease-in"
          From: "opacity-100 scale-100"
          To: "opacity-0 scale-95"
      -->
      <div class="absolute inset-x-0 top-0 origin-top transform p-2 transition lg:hidden">
        <div class="overflow-hidden rounded-lg bg-white shadow-lg ring-1 ring-black/5">
          <div class="flex items-center justify-between px-5 pt-4">
            <div>
              <img class="h-8 w-auto" src="https://tailwindui.com/plus/img/logos/mark.svg?color=teal&shade=500" alt="">
            </div>
            <div class="-mr-2">
              <button type="button" class="relative inline-flex items-center justify-center rounded-md bg-white p-2 text-slate-400 hover:bg-slate-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-teal-500">
                <span class="absolute -inset-0.5"></span>
                <span class="sr-only">Close menu</span>
                <svg class="size-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true" data-slot="icon">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M6 18 18 6M6 6l12 12" />
                </svg>
              </button>
            </div>
          </div>
          <div class="pb-6 pt-5">
            <div class="space-y-1 px-2">
              <a href="#" class="block rounded-md px-3 py-2 text-base font-medium text-slate-900 hover:bg-slate-50">Changelog</a>
              <a href="#" class="block rounded-md px-3 py-2 text-base font-medium text-slate-900 hover:bg-slate-50">About</a>
              <a href="#" class="block rounded-md px-3 py-2 text-base font-medium text-slate-900 hover:bg-slate-50">Partners</a>
              <a href="#" class="block rounded-md px-3 py-2 text-base font-medium text-slate-900 hover:bg-slate-50">News</a>
            </div>
            <div class="mt-6 px-5">
              <a href="#" class="block w-full rounded-md border border-transparent bg-teal-500 px-4 py-2 text-center font-medium text-white shadow hover:bg-teal-600">Login</a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="relative mx-auto mt-24 max-w-md px-6 pb-32 sm:max-w-3xl md:mt-32 lg:max-w-7xl lg:px-8">
      <h1 class="text-4xl font-bold tracking-tight text-white md:text-5xl lg:text-6xl">Customer Support</h1>
      <p class="mt-6 max-w-3xl text-xl text-slate-300">Varius facilisi mauris sed sit. Non sed et duis dui leo, vulputate id malesuada non. Cras aliquet purus dui laoreet diam sed lacus, fames. Dui, amet, nec sit pulvinar.</p>
    </div>
  </header>

  <main>
    <div class="bg-slate-50">
      <!-- Cards -->
      <section class="relative z-10 mx-auto -mt-32 max-w-md px-6 sm:max-w-3xl lg:max-w-7xl lg:px-8" aria-labelledby="contact-heading">
        <h2 class="sr-only" id="contact-heading">Contact us</h2>
        <div class="grid grid-cols-1 gap-y-20 lg:grid-cols-3 lg:gap-x-8 lg:gap-y-0">
          <div class="flex flex-col rounded-2xl bg-white shadow-xl">
            <div class="relative flex-1 px-6 pb-8 pt-16 md:px-8">
              <div class="absolute top-0 inline-block -translate-y-1/2 transform rounded-xl bg-teal-600 p-5 shadow-lg">
                <svg class="size-6 text-white" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true" data-slot="icon">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 0 0 2.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 0 1-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 0 0-1.091-.852H4.5A2.25 2.25 0 0 0 2.25 4.5v2.25Z" />
                </svg>
              </div>
              <h3 class="text-xl font-medium text-slate-900">Sales</h3>
              <p class="mt-4 text-base text-slate-500">Varius facilisi mauris sed sit. Non sed et duis dui leo, vulputate id malesuada non. Cras aliquet purus dui laoreet diam sed lacus, fames.</p>
            </div>
            <div class="rounded-bl-2xl rounded-br-2xl bg-slate-50 p-6 md:px-8">
              <a href="#" class="text-base font-medium text-teal-700 hover:text-teal-600">
                Contact us
                <span aria-hidden="true"> &rarr;</span>
              </a>
            </div>
          </div>
          <div class="flex flex-col rounded-2xl bg-white shadow-xl">
            <div class="relative flex-1 px-6 pb-8 pt-16 md:px-8">
              <div class="absolute top-0 inline-block -translate-y-1/2 transform rounded-xl bg-teal-600 p-5 shadow-lg">
                <svg class="size-6 text-white" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true" data-slot="icon">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M16.712 4.33a9.027 9.027 0 0 1 1.652 1.306c.51.51.944 1.064 1.306 1.652M16.712 4.33l-3.448 4.138m3.448-4.138a9.014 9.014 0 0 0-9.424 0M19.67 7.288l-4.138 3.448m4.138-3.448a9.014 9.014 0 0 1 0 9.424m-4.138-5.976a3.736 3.736 0 0 0-.88-1.388 3.737 3.737 0 0 0-1.388-.88m2.268 2.268a3.765 3.765 0 0 1 0 2.528m-2.268-4.796a3.765 3.765 0 0 0-2.528 0m4.796 4.796c-.181.506-.475.982-.88 1.388a3.736 3.736 0 0 1-1.388.88m2.268-2.268 4.138 3.448m0 0a9.027 9.027 0 0 1-1.306 1.652c-.51.51-1.064.944-1.652 1.306m0 0-3.448-4.138m3.448 4.138a9.014 9.014 0 0 1-9.424 0m5.976-4.138a3.765 3.765 0 0 1-2.528 0m0 0a3.736 3.736 0 0 1-1.388-.88 3.737 3.737 0 0 1-.88-1.388m2.268 2.268L7.288 19.67m0 0a9.024 9.024 0 0 1-1.652-1.306 9.027 9.027 0 0 1-1.306-1.652m0 0 4.138-3.448M4.33 16.712a9.014 9.014 0 0 1 0-9.424m4.138 5.976a3.765 3.765 0 0 1 0-2.528m0 0c.181-.506.475-.982.88-1.388a3.736 3.736 0 0 1 1.388-.88m-2.268 2.268L4.33 7.288m6.406 1.18L7.288 4.33m0 0a9.024 9.024 0 0 0-1.652 1.306A9.025 9.025 0 0 0 4.33 7.288" />
                </svg>
              </div>
              <h3 class="text-xl font-medium text-slate-900">Technical Support</h3>
              <p class="mt-4 text-base text-slate-500">Varius facilisi mauris sed sit. Non sed et duis dui leo, vulputate id malesuada non. Cras aliquet purus dui laoreet diam sed lacus, fames.</p>
            </div>
            <div class="rounded-bl-2xl rounded-br-2xl bg-slate-50 p-6 md:px-8">
              <a href="#" class="text-base font-medium text-teal-700 hover:text-teal-600">
                Contact us
                <span aria-hidden="true"> &rarr;</span>
              </a>
            </div>
          </div>
          <div class="flex flex-col rounded-2xl bg-white shadow-xl">
            <div class="relative flex-1 px-6 pb-8 pt-16 md:px-8">
              <div class="absolute top-0 inline-block -translate-y-1/2 transform rounded-xl bg-teal-600 p-5 shadow-lg">
                <svg class="size-6 text-white" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true" data-slot="icon">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M12 7.5h1.5m-1.5 3h1.5m-7.5 3h7.5m-7.5 3h7.5m3-9h3.375c.621 0 1.125.504 1.125 1.125V18a2.25 2.25 0 0 1-2.25 2.25M16.5 7.5V18a2.25 2.25 0 0 0 2.25 2.25M16.5 7.5V4.875c0-.621-.504-1.125-1.125-1.125H4.125C3.504 3.75 3 4.254 3 4.875V18a2.25 2.25 0 0 0 2.25 2.25h13.5M6 7.5h3v3H6v-3Z" />
                </svg>
              </div>
              <h3 class="text-xl font-medium text-slate-900">Media Inquiries</h3>
              <p class="mt-4 text-base text-slate-500">Varius facilisi mauris sed sit. Non sed et duis dui leo, vulputate id malesuada non. Cras aliquet purus dui laoreet diam sed lacus, fames.</p>
            </div>
            <div class="rounded-bl-2xl rounded-br-2xl bg-slate-50 p-6 md:px-8">
              <a href="#" class="text-base font-medium text-teal-700 hover:text-teal-600">
                Contact us
                <span aria-hidden="true"> &rarr;</span>
              </a>
            </div>
          </div>
        </div>
      </section>

      <!-- FAQ -->
      <section class="mx-auto max-w-md divide-y-2 divide-slate-200 px-6 py-24 sm:max-w-3xl lg:max-w-7xl lg:px-8 lg:py-32" aria-labelledby="faq-heading">
        <h2 class="text-3xl font-bold tracking-tight text-slate-900" id="faq-heading">Frequently asked questions</h2>
        <div class="mt-6 pt-10">
          <dl class="space-y-10 md:grid md:grid-cols-2 md:grid-rows-2 md:gap-x-8 md:gap-y-12 md:space-y-0">
            <div>
              <dt class="text-lg font-medium text-slate-900">Do I need a referral to see a rheumatologist?</dt>
              <dd class="mt-2 text-base text-slate-500">While some insurance plans require a referral from your primary care physician, many patients can schedule directly with us. We recommend checking with your insurance provider first, but we're happy to help you navigate the process regardless of your situation.</dd>
            </div>
            <div>
              <dt class="text-lg font-medium text-slate-900">What conditions do rheumatologists treat?</dt>
              <dd class="mt-2 text-base text-slate-500">We specialize in autoimmune and inflammatory conditions including rheumatoid arthritis, lupus, osteoarthritis, fibromyalgia, gout, psoriatic arthritis, and other joint, muscle, and connective tissue disorders. We also provide comprehensive diagnostic services for unexplained joint pain.</dd>
            </div>
            <div>
              <dt class="text-lg font-medium text-slate-900">How soon can I get an appointment?</dt>
              <dd class="mt-2 text-base text-slate-500">We understand that joint pain and autoimmune symptoms can significantly impact your daily life. We strive to schedule new patients within 1-2 weeks, with urgent cases often seen sooner. Established patients can typically be seen within a few days for follow-up appointments.</dd>
            </div>
            <div>
              <dt class="text-lg font-medium text-slate-900">What should I bring to my first appointment?</dt>
              <dd class="mt-2 text-base text-slate-500">Please bring a valid photo ID, insurance cards, a list of current medications, any recent lab results or imaging studies, and a summary of your symptoms including when they started and what makes them better or worse. This helps us provide the most effective care.</dd>
            </div>
            <div>
              <dt class="text-lg font-medium text-slate-900">Do you offer same-day lab results?</dt>
              <dd class="mt-2 text-base text-slate-500">Yes! Our on-site laboratory provides rapid results for most common rheumatology tests, often within hours rather than days. This allows us to adjust treatment plans quickly and provide you with answers during your visit whenever possible.</dd>
            </div>
            <div>
              <dt class="text-lg font-medium text-slate-900">What insurance plans do you accept?</dt>
              <dd class="mt-2 text-base text-slate-500">We accept most major insurance plans including Medicare, Medicaid, and most commercial insurers. Our billing team is experienced in rheumatology coverage and can help verify your benefits before your appointment. We also offer payment plans for uninsured patients.</dd>
            </div>
          </dl>
        </div>
      </section>
    </div>

    <!-- CTA Section -->
    <section class="relative bg-white" aria-labelledby="join-heading">
      <div class="absolute inset-x-0 hidden h-1/2 bg-slate-50 lg:block" aria-hidden="true"></div>
      <div class="mx-auto max-w-7xl bg-teal-600 lg:bg-transparent lg:px-8">
        <div class="lg:grid lg:grid-cols-12">
          <div class="relative z-10 lg:col-span-4 lg:col-start-1 lg:row-start-1 lg:bg-transparent lg:py-16">
            <div class="absolute inset-x-0 h-1/2 bg-slate-50 lg:hidden" aria-hidden="true"></div>
            <div class="mx-auto max-w-md px-6 sm:max-w-3xl lg:max-w-none lg:p-0">
              <img class="relative aspect-[10/6] w-full rounded-3xl object-cover shadow-2xl sm:aspect-[2/1] lg:aspect-square" src="https://images.unsplash.com/photo-1507207611509-ec012433ff52?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=934&q=80" alt="">
            </div>
          </div>

          <div class="relative bg-teal-600 lg:col-span-10 lg:col-start-3 lg:row-start-1 lg:grid lg:grid-cols-10 lg:items-center lg:rounded-3xl">
            <div class="absolute inset-0 hidden overflow-hidden rounded-3xl lg:block" aria-hidden="true">
              <svg class="absolute bottom-full left-full -translate-x-2/3 translate-y-1/3 transform xl:bottom-auto xl:top-0 xl:translate-y-0" width="404" height="384" fill="none" viewBox="0 0 404 384" aria-hidden="true">
                <defs>
                  <pattern id="64e643ad-2176-4f86-b3d7-f2c5da3b6a6d" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
                    <rect x="0" y="0" width="4" height="4" class="text-teal-500" fill="currentColor" />
                  </pattern>
                </defs>
                <rect width="404" height="384" fill="url(#64e643ad-2176-4f86-b3d7-f2c5da3b6a6d)" />
              </svg>
              <svg class="absolute top-full -translate-x-1/3 -translate-y-1/3 transform xl:-translate-y-1/2" width="404" height="384" fill="none" viewBox="0 0 404 384" aria-hidden="true">
                <defs>
                  <pattern id="64e643ad-2176-4f86-b3d7-f2c5da3b6a6d" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
                    <rect x="0" y="0" width="4" height="4" class="text-teal-500" fill="currentColor" />
                  </pattern>
                </defs>
                <rect width="404" height="384" fill="url(#64e643ad-2176-4f86-b3d7-f2c5da3b6a6d)" />
              </svg>
            </div>
            <div class="relative mx-auto max-w-md space-y-6 px-6 py-12 sm:max-w-3xl sm:py-16 lg:col-span-6 lg:col-start-4 lg:max-w-none lg:p-0">
              <h2 class="text-3xl font-bold tracking-tight text-white" id="join-heading">Join our team</h2>
              <p class="text-lg text-white">Varius facilisi mauris sed sit. Non sed et duis dui leo, vulputate id malesuada non. Cras aliquet purus dui laoreet diam sed lacus, fames.</p>
              <a class="block w-full rounded-md border border-transparent bg-white px-5 py-3 text-center text-base font-medium text-teal-700 shadow-md hover:bg-slate-50 sm:inline-block sm:w-auto" href="#">Explore open positions</a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Newsletter Section -->
    <section class="mx-auto max-w-md px-6 py-24 sm:max-w-3xl lg:flex lg:max-w-7xl lg:items-center lg:px-8 lg:py-32" aria-labelledby="newsletter-heading">
      <div class="lg:w-0 lg:flex-1">
        <h2 class="text-3xl font-bold tracking-tight text-slate-900 sm:text-4xl" id="newsletter-heading">Sign up for our newsletter</h2>
        <p class="mt-3 max-w-3xl text-lg text-slate-500">Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui Lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat fugiat.</p>
      </div>
      <div class="mt-8 lg:ml-8 lg:mt-0">
        <form class="sm:flex">
          <label for="email-address" class="sr-only">Email address</label>
          <input id="email-address" name="email-address" type="email" autocomplete="email" required class="w-full rounded-md border border-slate-300 px-5 py-3 placeholder-slate-400 shadow-sm focus:border-teal-500 focus:ring-1 focus:ring-teal-500 sm:max-w-xs" placeholder="Enter your email">
          <div class="mt-3 rounded-md shadow sm:ml-3 sm:mt-0 sm:shrink-0">
            <button type="submit" class="flex w-full items-center justify-center rounded-md border border-transparent bg-teal-600 px-5 py-3 text-base font-medium text-white hover:bg-teal-700 focus:outline-none focus:ring-2 focus:ring-teal-500 focus:ring-offset-2">Notify me</button>
          </div>
        </form>
        <p class="mt-3 text-sm text-slate-500">
          We care about the protection of your data. Read our
          <a href="#" class="font-medium underline">Privacy Policy.</a>
        </p>
      </div>
    </section>
  </main>

  <footer class="bg-slate-50" aria-labelledby="footer-heading">
    <h2 id="footer-heading" class="sr-only">Footer</h2>
    <div class="mx-auto max-w-md px-6 py-12 sm:max-w-7xl lg:px-8 lg:py-16">
      <div class="xl:grid xl:grid-cols-3 xl:gap-8">
        <div class="space-y-8 xl:col-span-1">
          <img class="h-10" src="https://tailwindui.com/plus/img/logos/mark.svg?color=tealGray&shade=300" alt="Company name">
          <p class="text-base text-slate-500">Making the world a better place through constructing elegant hierarchies.</p>
          <div class="flex space-x-6">
            <a href="#" class="text-slate-400 hover:text-slate-500">
              <span class="sr-only">Facebook</span>
              <svg class="size-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                <path fill-rule="evenodd" d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z" clip-rule="evenodd" />
              </svg>
            </a>
            <a href="#" class="text-slate-400 hover:text-slate-500">
              <span class="sr-only">Instagram</span>
              <svg class="size-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                <path fill-rule="evenodd" d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z" clip-rule="evenodd" />
              </svg>
            </a>
            <a href="#" class="text-slate-400 hover:text-slate-500">
              <span class="sr-only">X</span>
              <svg class="size-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                <path d="M13.6823 10.6218L20.2391 3H18.6854L12.9921 9.61788L8.44486 3H3.2002L10.0765 13.0074L3.2002 21H4.75404L10.7663 14.0113L15.5685 21H20.8131L13.6819 10.6218H13.6823ZM11.5541 13.0956L10.8574 12.0991L5.31391 4.16971H7.70053L12.1742 10.5689L12.8709 11.5655L18.6861 19.8835H16.2995L11.5541 13.096V13.0956Z" />
              </svg>
            </a>
            <a href="#" class="text-slate-400 hover:text-slate-500">
              <span class="sr-only">GitHub</span>
              <svg class="size-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd" />
              </svg>
            </a>
            <a href="#" class="text-slate-400 hover:text-slate-500">
              <span class="sr-only">Dribbble</span>
              <svg class="size-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                <path fill-rule="evenodd" d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10c5.51 0 10-4.48 10-10S17.51 2 12 2zm6.605 4.61a8.502 8.502 0 011.93 5.314c-.281-.054-3.101-.629-5.943-.271-.065-.141-.12-.293-.184-.445a25.416 25.416 0 00-.564-1.236c3.145-1.28 4.577-3.124 4.761-3.362zM12 3.475c2.17 0 4.154.813 5.662 2.148-.152.216-1.443 1.941-4.48 3.08-1.399-2.57-2.95-4.675-3.189-5A8.687 8.687 0 0112 3.475zm-3.633.803a53.896 53.896 0 013.167 4.935c-3.992 1.063-7.517 1.04-7.896 1.04a8.581 8.581 0 014.729-5.975zM3.453 12.01v-.26c.37.01 4.512.065 8.775-1.215.25.477.477.965.694 1.453-.109.033-.228.065-.336.098-4.404 1.42-6.747 5.303-6.942 5.629a8.522 8.522 0 01-2.19-5.705zM12 20.547a8.482 8.482 0 01-5.239-1.8c.152-.315 1.888-3.656 6.703-5.337.022-.01.033-.01.054-.022a35.318 35.318 0 011.823 6.475 8.4 8.4 0 01-3.341.684zm4.761-1.465c-.086-.52-.542-3.015-1.659-6.084 2.679-.423 5.022.271 5.314.369a8.468 8.468 0 01-3.655 5.715z" clip-rule="evenodd" />
              </svg>
            </a>
          </div>
        </div>
        <div class="mt-12 grid grid-cols-2 gap-8 xl:col-span-2 xl:mt-0">
          <div class="md:grid md:grid-cols-2 md:gap-8">
            <div>
              <h3 class="text-base font-medium text-slate-900">Solutions</h3>
              <ul role="list" class="mt-4 space-y-4">
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">Marketing</a>
                </li>
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">Analytics</a>
                </li>
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">Commerce</a>
                </li>
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">Insights</a>
                </li>
              </ul>
            </div>
            <div class="mt-12 md:mt-0">
              <h3 class="text-base font-medium text-slate-900">Support</h3>
              <ul role="list" class="mt-4 space-y-4">
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">Pricing</a>
                </li>
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">Documentation</a>
                </li>
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">Guides</a>
                </li>
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">API Status</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="md:grid md:grid-cols-2 md:gap-8">
            <div>
              <h3 class="text-base font-medium text-slate-900">Company</h3>
              <ul role="list" class="mt-4 space-y-4">
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">About</a>
                </li>
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">Blog</a>
                </li>
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">Jobs</a>
                </li>
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">Press</a>
                </li>
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">Partners</a>
                </li>
              </ul>
            </div>
            <div class="mt-12 md:mt-0">
              <h3 class="text-base font-medium text-slate-900">Legal</h3>
              <ul role="list" class="mt-4 space-y-4">
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">Claim</a>
                </li>
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">Privacy</a>
                </li>
                <li>
                  <a href="#" class="text-base text-slate-500 hover:text-slate-900">Terms</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="mt-12 border-t border-slate-200 pt-8">
        <p class="text-base text-slate-400 xl:text-center">&copy; 2025 Your Company, Inc. All rights reserved.</p>
      </div>
    </div>
  </footer>
</div>
</template>