<template>
  <section id="contact" class="py-16 md:py-24 bg-gradient-to-b from-gray-900 to-gray-800 text-white">
    <div class="container mx-auto max-w-4xl px-4">
      <h2 class="text-3xl sm:text-4xl lg:text-5xl font-bold text-[#A97A13] text-center mb-8">
      Contact Me
    </h2>
      <div class="flex flex-col md:flex-row justify-around items-center text-center space-y-8 md:space-y-0 md:space-x-8">
        <!-- Address -->
        <div class="flex flex-col items-center">
          <img src="/static/images/location-arrow-svgrepo-com.svg" alt="Location" class="w-12 h-12 mb-2">
          <p class="text-lg font-semibold">Location</p>
          <p class="text-gray-400">New Delhi, India</p>
        </div>

        <!-- Email -->
        <div class="flex flex-col items-center">
          <img src="/static/images/email-svgrepo-com.svg" alt="Email" class="w-12 h-12 mb-2">
          <p class="text-lg text-#A97A13 font-semibold">Email</p>
          <p class="text-gray-500">karunesh@example.com</p>
        </div>

        <!-- Phone -->
        <div class="flex flex-col items-center">
          <img src="/static/images/phone-calling-svgrepo-com.svg" alt="Phone" class="w-12 h-12 mb-2">
          <p class="text-lg font-semibold">Phone</p>
          <p class="text-gray-500">+91 12345 67890</p>
        </div>
      </div>

      <!-- Contact Form -->
      <form class="mt-12 space-y-6">
        <!-- Name -->
        <div class="flex flex-col">
          <label for="name" class="text-lg font-semibold mb-2">Your Name</label>
          <input type="text" id="name" class="py-3 px-4 rounded-lg bg-gray-800 text-gray-300 focus:outline-none focus:ring-2 focus:ring-[#A97A13]">
        </div>

        <!-- Email -->
        <div class="flex flex-col">
          <label for="email" class="text-lg font-semibold mb-2">Your Email</label>
          <input type="email" id="email" class="py-3 px-4 rounded-lg bg-gray-800 text-gray-300 focus:outline-none focus:ring-2 focus:ring-[#A97A13]">
        </div>

        <!-- Message -->
        <div class="flex flex-col">
          <label for="message" class="text-lg font-semibold mb-2">Message</label>
          <textarea id="message" rows="5" class="py-3 px-4 rounded-lg bg-gray-800 text-gray-300 focus:outline-none focus:ring-2 focus:ring-[#A97A13]"></textarea>
        </div>

        <!-- Submit Button -->
        <div class="text-center">
          <button type="submit" class="py-3 px-8 bg-[#A97A13] hover:bg-yellow-600 text-white font-bold rounded-lg transition duration-300">
            Send Message
          </button>
        </div>
      </form>
    </div>
  </section>
</template>



