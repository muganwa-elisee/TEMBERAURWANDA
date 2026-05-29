<template>
  <footer class="bg-gradient-to-br from-green-950 via-green-900 to-black text-white">
    
    <!-- Main Footer -->
    <div class="max-w-7xl mx-auto px-6 lg:px-12 py-16">

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-12">

        <!-- Brand -->
        <div>
          <h2 class="text-3xl font-black text-yellow-400 mb-5">
            TEMBERA URWANDA
          </h2>

          <p class="text-green-200 leading-relaxed">
            Discover the beauty of the Land of a Thousand Hills.
            Explore culture, wildlife, adventure, and unforgettable
            experiences across Rwanda.
          </p>

          <!-- Social Icons -->
          <div class="flex gap-4 mt-6">
            <div class="w-10 h-10 rounded-full bg-white/10 flex items-center justify-center hover:bg-yellow-400 hover:text-black transition-all duration-300 cursor-pointer">
              F
            </div>

            <div class="w-10 h-10 rounded-full bg-white/10 flex items-center justify-center hover:bg-yellow-400 hover:text-black transition-all duration-300 cursor-pointer">
              I
            </div>

            <div class="w-10 h-10 rounded-full bg-white/10 flex items-center justify-center hover:bg-yellow-400 hover:text-black transition-all duration-300 cursor-pointer">
              X
            </div>
          </div>
        </div>

        <!-- Quick Links -->
        <div>
          <h3 class="text-xl font-bold text-yellow-300 mb-6">
            Quick Links
          </h3>

          <ul class="space-y-3 text-green-200">
            <li>
              <RouterLink to="/" class="hover:text-yellow-300 transition">
                Home
              </RouterLink>
            </li>

            <li>
              <RouterLink to="/about" class="hover:text-yellow-300 transition">
                About
              </RouterLink>
            </li>

            <li>
              <RouterLink to="/services" class="hover:text-yellow-300 transition">
                Services
              </RouterLink>
            </li>

            <li>
              <RouterLink to="/gallery" class="hover:text-yellow-300 transition">
                Gallery
              </RouterLink>
            </li>

            <li>
              <RouterLink to="/contact" class="hover:text-yellow-300 transition">
                Contact
              </RouterLink>
            </li>
          </ul>
        </div>

        <!-- Destinations -->
        <div>
          <h3 class="text-xl font-bold text-yellow-300 mb-6">
            Destinations
          </h3>

          <ul class="space-y-3 text-green-200">
            <li>
              <RouterLink to="/north" class="hover:text-yellow-300 transition">
                Northern Province
              </RouterLink>
            </li>

            <li>
              <RouterLink to="/south" class="hover:text-yellow-300 transition">
                Southern Province
              </RouterLink>
            </li>

            <li>
              <RouterLink to="/east" class="hover:text-yellow-300 transition">
                Eastern Province
              </RouterLink>
            </li>

            <li>
              <RouterLink to="/west" class="hover:text-yellow-300 transition">
                Western Province
              </RouterLink>
            </li>

            <li>
              <RouterLink to="/kigali" class="hover:text-yellow-300 transition">
                Kigali City
              </RouterLink>
            </li>
          </ul>
        </div>

        <!-- Contact -->
        <div>
          <h3 class="text-xl font-bold text-yellow-300 mb-6">
            Contact
          </h3>

          <ul class="space-y-4 text-green-200">
            <li>
              📧 ahantunyaburanga@gmail.com
            </li>

            <li>
              📞 +250 788 212 800
            </li>

            <li>
              📍 Kagugu, Kigali - Rwanda
            </li>
          </ul>

          <!-- Newsletter -->
          <div class="mt-8">
            <input
              type="email"
              placeholder="Your email"
              class="w-full px-4 py-3 rounded-xl bg-white/10 border border-white/10 focus:outline-none focus:ring-2 focus:ring-yellow-400"
            />

            <button
              class="mt-3 w-full bg-yellow-400 hover:bg-yellow-300 text-black font-bold py-3 rounded-xl transition-all duration-300"
            >
              Subscribe
            </button>
          </div>
        </div>
      </div>

      <!-- Bottom Footer -->
      <div class="border-t border-green-700 mt-14 pt-6 text-center text-green-300">
        <p>
          © 2026 Visit Rwanda. All Rights Reserved.
        </p>
      </div>
    </div>
  </footer>
</template>

<script setup>
</script>