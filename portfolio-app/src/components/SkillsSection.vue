<template>
  <section id="skills" class="py-16 px-4 sm:px-6 lg:px-8 bg-gradient-to-br from-gray-50 to-indigo-50">
    <div class="max-w-7xl mx-auto">
      <div class="text-center mb-16">
        <h2 class="text-4xl font-bold text-gray-900 mb-4">Skills & Technologies</h2>
        <p class="text-xl text-gray-600">Technologies I work with</p>
      </div>
      
      <!-- Skills Grid -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 mb-12">
        <div v-for="skill in skills" :key="skill.name" 
             class="text-center p-6 bg-white rounded-xl shadow-lg hover:shadow-xl transition-all duration-300 hover:scale-105 hover:-translate-y-2">
          <div class="text-4xl mb-4">{{ skill.icon }}</div>
          <h3 class="text-lg font-semibold text-gray-900 mb-2">{{ skill.name }}</h3>
          <p class="text-gray-600 text-sm">{{ skill.description }}</p>
        </div>
      </div>

      <!-- Certifications -->
      <div class="bg-white rounded-2xl shadow-xl p-8">
        <h3 class="text-2xl font-bold text-gray-900 mb-6 text-center">Certifications</h3>
        <div class="max-w-md mx-auto">
          <div class="bg-gradient-to-r from-indigo-50 to-purple-50 p-6 rounded-xl text-center">
            <div class="text-3xl mb-3">🇯🇵</div>
            <h4 class="text-xl font-semibold text-gray-900 mb-2">Japanese Language Proficiency Test</h4>
            <p class="text-indigo-600 font-semibold">JLPT N3 Level</p>
            <p class="text-sm text-gray-600 mt-2">July 2023</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const skills = ref([
  { name: 'Java', icon: '☕', description: 'Programming Language' },
  { name: 'JavaScript', icon: '🟨', description: 'Programming Language' },
  { name: 'VueJS 2 & 3', icon: '⚡', description: 'Frontend Framework' },
  { name: 'NuxtJS', icon: '🟢', description: 'Vue Framework' },
  { name: 'ExpressJS', icon: '🚀', description: 'Backend Framework' },
  { name: 'Spring Boot', icon: '🍃', description: 'Java Framework' },
  { name: 'Tailwind CSS', icon: '🎨', description: 'CSS Framework' },
  { name: 'Git', icon: '📝', description: 'Version Control' },
  { name: 'Docker', icon: '🐳', description: 'Containerization' },
  { name: 'Windows', icon: '🪟', description: 'Operating System' },
  { name: 'Linux', icon: '🐧', description: 'Operating System' }
])
</script>
