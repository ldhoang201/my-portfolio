<template>
  <section id="contact" class="py-16 px-4 sm:px-6 lg:px-8 bg-gradient-to-br from-indigo-600 to-purple-700 relative overflow-hidden">
    <!-- Animated background elements -->
    <div class="absolute inset-0 overflow-hidden">
      <div class="absolute top-0 left-0 w-full h-full bg-gradient-to-br from-indigo-600/90 to-purple-700/90"></div>
      <div class="absolute -top-20 -right-20 w-40 h-40 bg-white/10 rounded-full blur-2xl animate-pulse"></div>
      <div class="absolute -bottom-20 -left-20 w-40 h-40 bg-white/10 rounded-full blur-2xl animate-pulse" style="animation-delay: 1s;"></div>
    </div>
    
    <div class="max-w-7xl mx-auto text-center relative z-10">
      <h2 class="text-4xl font-bold text-white mb-4">Let's Work Together</h2>
      <p class="text-xl text-indigo-100 mb-8">Have a project in mind? Let's discuss it!</p>
      
      <!-- Contact Info -->
      <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6 mb-12">
        <div class="bg-white/10 backdrop-blur-sm rounded-xl p-6 hover:bg-white/20 transition-all duration-300">
          <div class="text-2xl mb-2">📞</div>
          <div class="text-white font-semibold">Phone</div>
          <div class="text-indigo-100">0982687165</div>
        </div>
        <div class="bg-white/10 backdrop-blur-sm rounded-xl p-6 hover:bg-white/20 transition-all duration-300">
          <div class="text-2xl mb-2">📧</div>
          <div class="text-white font-semibold">Email</div>
          <div class="text-indigo-100">lehoangtptn@gmail.com</div>
        </div>
        <div class="bg-white/10 backdrop-blur-sm rounded-xl p-6 hover:bg-white/20 transition-all duration-300">
          <div class="text-2xl mb-2">📍</div>
          <div class="text-white font-semibold">Location</div>
          <div class="text-indigo-100">Hai Ba Trung, Ha Noi</div>
        </div>
        <div class="bg-white/10 backdrop-blur-sm rounded-xl p-6 hover:bg-white/20 transition-all duration-300">
          <div class="text-2xl mb-2">💻</div>
          <div class="text-white font-semibold">GitHub</div>
          <div class="text-indigo-100">ldhoang201</div>
        </div>
      </div>
      
      <div class="flex flex-col sm:flex-row gap-4 justify-center mb-12">
        <a-button type="primary" size="large" class="bg-white text-indigo-600 border-white hover:bg-gray-100 hover:scale-105 transition-all duration-300">
          <template #icon><MailOutlined /></template>
          Send Email
        </a-button>
        <a-button size="large" class="border-white text-white hover:bg-white hover:text-indigo-600 hover:scale-105 transition-all duration-300">
          <template #icon><LinkedinOutlined /></template>
          LinkedIn
        </a-button>
      </div>
      <div class="text-indigo-100">
        <p>© 2024 Le Duoc Hoang. All rights reserved.</p>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import { MailOutlined, LinkedinOutlined } from '@ant-design/icons-vue'
</script>
