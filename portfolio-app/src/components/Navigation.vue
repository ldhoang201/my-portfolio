<template>
  <nav class="fixed top-0 w-full bg-white/90 backdrop-blur-lg z-50 shadow-lg border-b border-white/20">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex justify-between items-center py-4">
        <div class="text-2xl font-bold bg-gradient-to-r from-indigo-600 to-purple-600 bg-clip-text text-transparent">
          Le Duoc Hoang
        </div>
        <div class="hidden md:flex space-x-8">
          <a href="#home" class="text-gray-700 hover:text-indigo-600 transition-all duration-300 hover:scale-105">Home</a>
          <a href="#about" class="text-gray-700 hover:text-indigo-600 transition-all duration-300 hover:scale-105">About</a>
          <a href="#education" class="text-gray-700 hover:text-indigo-600 transition-all duration-300 hover:scale-105">Education</a>
          <a href="#experience" class="text-gray-700 hover:text-indigo-600 transition-all duration-300 hover:scale-105">Experience</a>
          <a href="#skills" class="text-gray-700 hover:text-indigo-600 transition-all duration-300 hover:scale-105">Skills</a>
          <a href="#projects" class="text-gray-700 hover:text-indigo-600 transition-all duration-300 hover:scale-105">Projects</a>
          <a href="#contact" class="text-gray-700 hover:text-indigo-600 transition-all duration-300 hover:scale-105">Contact</a>
        </div>
        <a-button type="primary" class="md:hidden">
          <template #icon><MenuOutlined /></template>
        </a-button>
      </div>
    </div>
  </nav>
</template>

<script setup lang="ts">
import { MenuOutlined } from '@ant-design/icons-vue'
</script>
