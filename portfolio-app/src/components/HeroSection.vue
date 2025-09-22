<template>
  <section id="home" class="pt-20 pb-16 px-4 sm:px-6 lg:px-8 relative overflow-hidden">
    <!-- Animated background elements -->
    <div class="absolute inset-0 overflow-hidden">
      <div class="absolute -top-40 -right-40 w-80 h-80 bg-gradient-to-br from-indigo-400/20 to-purple-600/20 rounded-full blur-3xl animate-pulse"></div>
      <div class="absolute -bottom-40 -left-40 w-80 h-80 bg-gradient-to-br from-blue-400/20 to-cyan-600/20 rounded-full blur-3xl animate-pulse" style="animation-delay: 1s;"></div>
    </div>
    
    <div class="max-w-7xl mx-auto relative z-10">
      <div class="text-center">
        <div class="mb-8">
          <div class="w-32 h-32 mx-auto mb-6 bg-gradient-to-r from-indigo-500 to-purple-600 rounded-full flex items-center justify-center shadow-2xl hover:scale-110 transition-transform duration-500 animate-bounce">
            <span class="text-4xl text-white font-bold">LH</span>
          </div>
          <h1 class="text-5xl md:text-7xl font-bold text-gray-900 mb-4 animate-fade-in">
            Le Duoc Hoang
          </h1>
          <h2 class="text-2xl md:text-3xl bg-gradient-to-r from-indigo-600 to-purple-600 bg-clip-text text-transparent mb-6 animate-fade-in" style="animation-delay: 0.2s;">
            VueJS Developer
          </h2>
          <p class="text-xl text-gray-600 max-w-3xl mx-auto mb-8 animate-fade-in" style="animation-delay: 0.4s;">
            Seeking to develop strong full-stack web development skills while working in a collaborative, international team environment. 
            Passionate about building scalable applications and improving communication skills.
          </p>
          <div class="flex flex-col sm:flex-row gap-4 justify-center animate-fade-in" style="animation-delay: 0.6s;">
            <a-button type="primary" size="large" class="px-8 py-4 h-auto hover:scale-105 transition-transform duration-300">
              View My Work
            </a-button>
            <a-button size="large" class="px-8 py-4 h-auto hover:scale-105 transition-transform duration-300">
              Download CV
            </a-button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
// No additional imports needed for this component
</script>
