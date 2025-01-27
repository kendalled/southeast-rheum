<template>
    <section class="bg-gray-50 text-gray-800">
      <!-- Hero Section -->
      <div class="bg-teal-600 text-teal-50 py-12 px-4 text-center">
        <h1 class="text-3xl md:text-4xl font-bold">Comprehensive Rheumatology Services in Orlando</h1>
        <p class="mt-4 text-lg">
          Trusted care from the leading rheumatologist in Orlando. We specialize in diagnosing and managing arthritis, autoimmune diseases, and other rheumatic conditions.
        </p>
      </div>
  
      <!-- Content Section -->
      <div class="max-w-7xl mx-auto px-4 py-12 space-y-16">
        <!-- Section 1: Arthritis Care -->
        <div class="grid md:grid-cols-2 gap-8 items-center">
          <div>
            <h2 class="text-2xl font-semibold text-teal-600">Arthritis Care</h2>
            <p class="mt-4 text-gray-700 leading-relaxed">
              Our experienced team offers personalized treatment plans for a variety of arthritis conditions. As the go-to rheumatologist in Orlando, we aim to relieve pain and improve quality of life.
            </p>
            <ul class="mt-4 list-disc list-inside text-gray-700">
              <li>Rheumatoid arthritis</li>
              <li>Osteoarthritis</li>
              <li>Psoriatic arthritis</li>
              <li>Juvenile arthritis</li>
            </ul>
          </div>
          <div class="flex justify-center">
            <img
                src="/arthritis.jpeg"
                alt="Arthritis care"
                class="rounded-lg shadow-md object-cover w-full h-96 max-w-2xl"
            />
        </div>
        </div>
  
        <!-- Section 2: Autoimmune Disease Management -->
        <div class="grid md:grid-cols-2 gap-8 items-center">
            <div class="flex justify-center">
            <img
                src="/autoimmune.jpg"
                alt="Autoimmune care"
                class="rounded-lg shadow-md object-cover w-full h-96 max-w-2xl"
            />
        </div>
          <div>
            <h2 class="text-2xl font-semibold text-teal-600">Autoimmune Disease Management</h2>
            <p class="mt-4 text-gray-700 leading-relaxed">
              Our specialists are trained to diagnose and treat autoimmune diseases with precision and care. Conveniently located in Orlando, we provide expert guidance to manage chronic conditions.
            </p>
            <ul class="mt-4 list-disc list-inside text-gray-700">
              <li>Lupus</li>
              <li>Sjögren’s syndrome</li>
              <li>Scleroderma</li>
              <li>Vasculitis</li>
            </ul>
          </div>
        </div>
  
        <!-- Section 3: Infusion Therapy -->
        <div class="grid md:grid-cols-2 gap-8 items-center">
          <div>
            <h2 class="text-2xl font-semibold text-teal-600">Infusion Therapy</h2>
            <p class="mt-4 text-gray-700 leading-relaxed">
              For patients requiring biologic medications, our Orlando clinic provides safe and convenient infusion therapy services in a comfortable environment.
            </p>
            <ul class="mt-4 list-disc list-inside text-gray-700">
              <li>Biologic treatments for rheumatoid arthritis</li>
              <li>Osteoporosis treatments</li>
              <li>Immunosuppressive medications</li>
            </ul>
          </div>
          <div class="flex justify-center">
            <img
                src="/infusion.jpeg"
                alt="Infusion therapy"
                class="rounded-lg shadow-md object-cover w-full h-96 max-w-2xl"
            />
        </div>
        </div>
  
        <!-- Section 4: Diagnostic Services -->
        <div class="grid md:grid-cols-2 gap-8 items-center">
          <div class="flex justify-center">
            <img
                src="/x-ray.jpeg"
                alt="Diagnostic services"
                class="rounded-lg shadow-md object-cover w-full h-96 max-w-2xl"
            />
        </div>
          <div>
            <h2 class="text-2xl font-semibold text-teal-600">Advanced Diagnostic Services</h2>
            <p class="mt-4 text-gray-700 leading-relaxed">
              As a leading rheumatologist in Orlando, we use cutting-edge diagnostic tools to identify and monitor rheumatic conditions.
            </p>
            <ul class="mt-4 list-disc list-inside text-gray-700">
              <li>X-rays and MRIs</li>
              <li>Blood tests and biomarkers</li>
              <li>Joint fluid analysis</li>
            </ul>
          </div>
        </div>
  
        <!-- Call to Action -->
        <div class="text-center">
          <a
            href="/contact"
            class="inline-block bg-teal-600 text-white font-medium py-3 px-6 rounded-md shadow hover:bg-teal-700 transition duration-200"
          >
            Schedule Your Appointment Today
          </a>
          <p class="mt-4 text-gray-700">
            Experience the difference with a trusted rheumatologist in Orlando. Let us help you take control of your health.
          </p>
        </div>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: "ServicesContent",
  };
  </script>
  