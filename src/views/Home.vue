<template>
  <div class="bg-black text-white overflow-hidden">
    <!-- HERO SECTION -->
    <section class="relative min-h-screen flex items-center justify-center overflow-hidden">
      <!-- Background Image -->
      <div
        class="absolute inset-0 bg-cover bg-center scale-110 animate-slowZoom"
        style="background-image: url('@/assets/Images/FLAG.png');"
      ></div>

      <!-- Overlay -->
      <div class="absolute inset-0 bg-gradient-to-br from-black/80 via-black/50 to-green-900/60"></div>

      <!-- Decorative Lights -->
      <div class="absolute top-0 left-0 w-96 h-96 bg-green-500/20 blur-3xl rounded-full"></div>
      <div class="absolute bottom-0 right-0 w-[500px] h-[500px] bg-emerald-400/10 blur-3xl rounded-full"></div>
      <div class="absolute top-40 right-20 w-40 h-40 bg-yellow-400/20 blur-2xl rounded-full"></div>

      <!-- Content -->
      <div class="relative z-10 max-w-7xl mx-auto px-6 lg:px-12 grid lg:grid-cols-2 gap-16 items-center">
        <!-- Left Side -->
        <div>
          <!-- Badge -->
          <div class="inline-flex items-center gap-3 px-5 py-2 rounded-full bg-white/10 backdrop-blur-lg border border-white/10 shadow-2xl mb-8">
            <div class="w-3 h-3 rounded-full bg-green-400 animate-pulse"></div>
            <span class="uppercase tracking-[0.2em] text-sm text-green-200 font-semibold">
              Explore Rwanda
            </span>
          </div>

          <!-- Heading -->
          <h1 class="text-5xl md:text-7xl xl:text-8xl font-black leading-tight tracking-tight drop-shadow-2xl">
            Discover the
            <span class="text-green-400">Beauty</span>
            of Rwanda
          </h1>

          <!-- Paragraph -->
          <p class="mt-8 text-lg md:text-xl text-gray-200 leading-relaxed max-w-2xl">
            Travel through breathtaking hills, luxury eco-lodges,
            vibrant culture, wildlife adventures, and unforgettable
            experiences in the heart of Africa.
          </p>

          <!-- Buttons -->
          <div class="mt-10 flex flex-col sm:flex-row gap-5">
            <button class="px-8 py-4 rounded-2xl bg-green-500 hover:bg-green-600 transition-all duration-300 font-semibold text-lg shadow-2xl hover:scale-105 hover:shadow-green-500/40">
              Start Journey
            </button>

            <button class="px-8 py-4 rounded-2xl bg-white/10 border border-white/20 backdrop-blur-lg hover:bg-white/20 transition-all duration-300 font-semibold text-lg">
              View Destinations
            </button>
          </div>

          <!-- Stats -->
          <div class="mt-14 grid grid-cols-2 md:grid-cols-4 gap-5">
            <div class="bg-white/10 border border-white/10 backdrop-blur-xl rounded-3xl p-5 shadow-2xl hover:scale-105 transition-all duration-300">
              <h2 class="text-3xl font-bold text-green-400">1000+</h2>
              <p class="text-gray-300 mt-2 text-sm">Beautiful Hills</p>
            </div>

            <div class="bg-white/10 border border-white/10 backdrop-blur-xl rounded-3xl p-5 shadow-2xl hover:scale-105 transition-all duration-300">
              <h2 class="text-3xl font-bold text-yellow-400">4</h2>
              <p class="text-gray-300 mt-2 text-sm">National Parks</p>
            </div>

            <div class="bg-white/10 border border-white/10 backdrop-blur-xl rounded-3xl p-5 shadow-2xl hover:scale-105 transition-all duration-300">
              <h2 class="text-3xl font-bold text-cyan-400">24/7</h2>
              <p class="text-gray-300 mt-2 text-sm">Tourism Access</p>
            </div>

            <div class="bg-white/10 border border-white/10 backdrop-blur-xl rounded-3xl p-5 shadow-2xl hover:scale-105 transition-all duration-300">
              <h2 class="text-3xl font-bold text-pink-400">95%</h2>
              <p class="text-gray-300 mt-2 text-sm">Visitor Satisfaction</p>
            </div>
          </div>
        </div>

        <!-- Right Side Image Cards -->
        <div class="relative hidden lg:block">
          <div class="grid grid-cols-2 gap-6">
            <!-- Card 1 -->
            <div class="group relative overflow-hidden rounded-[30px] shadow-2xl h-80 hover:-translate-y-2 transition-all duration-500">
              <img
                src="https://images.unsplash.com/photo-1547471080-7cc2caa01a7e?q=80&w=1200&auto=format&fit=crop"
                class="w-full h-full object-cover group-hover:scale-110 transition-all duration-700"
              />

              <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>

              <div class="absolute bottom-5 left-5">
                <h3 class="text-2xl font-bold">Volcanoes</h3>
                <p class="text-gray-300 text-sm">Mountain Adventures</p>
              </div>
            </div>

            <!-- Card 2 -->
            <div class="group relative overflow-hidden rounded-[30px] shadow-2xl h-64 mt-20 hover:-translate-y-2 transition-all duration-500">
              <img
                src="https://images.unsplash.com/photo-1516426122078-c23e76319801?q=80&w=1200&auto=format&fit=crop"
                class="w-full h-full object-cover group-hover:scale-110 transition-all duration-700"
              />

              <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>

              <div class="absolute bottom-5 left-5">
                <h3 class="text-2xl font-bold">Wildlife</h3>
                <p class="text-gray-300 text-sm">Nature Experience</p>
              </div>
            </div>

            <!-- Card 3 -->
            <div class="group relative overflow-hidden rounded-[30px] shadow-2xl h-64 hover:-translate-y-2 transition-all duration-500">
              <img
                src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?q=80&w=1200&auto=format&fit=crop"
                class="w-full h-full object-cover group-hover:scale-110 transition-all duration-700"
              />

              <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>

              <div class="absolute bottom-5 left-5">
                <h3 class="text-2xl font-bold">Lakes</h3>
                <p class="text-gray-300 text-sm">Relaxing Views</p>
              </div>
            </div>

            <!-- Card 4 -->
            <div class="group relative overflow-hidden rounded-[30px] shadow-2xl h-80 -mt-16 hover:-translate-y-2 transition-all duration-500">
              <img
                src="https://images.unsplash.com/photo-1528127269322-539801943592?q=80&w=1200&auto=format&fit=crop"
                class="w-full h-full object-cover group-hover:scale-110 transition-all duration-700"
              />

              <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>

              <div class="absolute bottom-5 left-5">
                <h3 class="text-2xl font-bold">Culture</h3>
                <p class="text-gray-300 text-sm">Authentic Heritage</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Scroll Indicator -->
      <div class="absolute bottom-8 left-1/2 -translate-x-1/2 z-20 flex flex-col items-center">
        <span class="text-sm tracking-widest text-gray-300 mb-2 uppercase">
          Scroll
        </span>

        <div class="w-7 h-12 rounded-full border-2 border-white flex justify-center p-1">
          <div class="w-1.5 h-3 bg-white rounded-full animate-bounce"></div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
@keyframes slowZoom {
  0% {
    transform: scale(1);
  }

  100% {
    transform: scale(1.15);
  }
}

.animate-slowZoom {
  animation: slowZoom 20s ease-in-out infinite alternate;
}
</style>