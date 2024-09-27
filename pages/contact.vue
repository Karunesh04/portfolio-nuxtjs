<template>
  <section id="contact" class="p- mb-16 text-[#A97A13] rounded-xl">
    <div class="container mx-auto max-w-4xl px-4">
      <h2 class="text-3xl sm:text-4xl lg:text-5xl font-bold text-[#A97A13] text-center mb-8">
      Contact Me
    </h2>
      <div class="flex flex-col md:flex-row justify-around items-center text-center space-y-8 md:space-y-0 md:space-x-8">
        
        <div class="flex flex-col items-center">
          <img src="/static/images/location-arrow-svgrepo-com.svg" alt="Location" class="w-10 mb-2 icon">
          <p class="text-lg font-semibold">Location</p>
          <p class="text-gray-500">New Delhi, India</p>
        </div>

        <div class="flex flex-col items-center">
          <img src="/static/images/email-svgrepo-com.svg" alt="Email" class="w-10 mb-2 icon">
          <p class="text-lg text-#A97A13 font-semibold">Email</p>
          <p class="text-gray-500">karunesh@gmail.com</p>
        </div>

        <div class="flex flex-col items-center">
          <img src="/static/images/phone-calling-svgrepo-com.svg" alt="Phone" class="w-10 mb-2 icon">
          <p class="text-lg font-semibold">Phone</p>
          <p class="text-gray-500">+91 12345 67890</p>
        </div>
      </div>

      <form class="mt-12 space-y-6">

        <div class="flex flex-col">
          <label for="name" class="text-lg font-semibold mb-2">Your Name</label>
          <input type="text" id="name" class="py-3 px-4 rounded-lg bg-transparent text-gray-500 focus:outline-none ring-2 ring-[#A97A13]">
        </div>

        <div class="flex flex-col">
          <label for="email" class="text-lg font-semibold mb-2">Your Email</label>
          <input type="email" id="email" class="py-3 px-4 rounded-lg bg-transparent text-gray-500 focus:outline-none ring-2 ring-[#A97A13]">
        </div>

        <div class="flex flex-col">
          <label for="message" class="text-lg font-semibold mb-2">Message</label>
          <textarea id="message" rows="5" class="py-3 px-4 rounded-lg bg-transparent text-gray-500 focus:outline-none ring-2 ring-[#A97A13] resize-none"></textarea>
        </div>

        <div class="text-center">
          <button type="submit" class="text-white text-lg font-bold py-4 px-8 bg-[#A97A13] rounded-lg transition duration-300 icon">
            Send Message
          </button>
        </div>
      </form>
    </div>
  </section>
</template>



