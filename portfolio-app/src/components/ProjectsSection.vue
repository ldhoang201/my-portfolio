<template>
  <section id="projects" class="py-16 px-4 sm:px-6 lg:px-8 bg-white">
    <div class="max-w-7xl mx-auto">
      <div class="text-center mb-16">
        <h2 class="text-4xl font-bold text-gray-900 mb-4">Featured Projects</h2>
        <p class="text-xl text-gray-600">Some of my recent work</p>
      </div>
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div v-for="project in projects" :key="project.id" 
             class="bg-white rounded-xl shadow-lg overflow-hidden hover:shadow-2xl transition-all duration-500 hover:scale-105">
          <div class="h-48 bg-gradient-to-br from-indigo-400 to-purple-500 flex items-center justify-center">
            <span class="text-4xl text-white">{{ project.icon }}</span>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-semibold text-gray-900 mb-2">{{ project.title }}</h3>
            <p class="text-gray-600 mb-4">{{ project.description }}</p>
            <div class="flex flex-wrap gap-2 mb-4">
              <span v-for="tech in project.technologies" :key="tech" 
                    class="px-3 py-1 bg-gradient-to-r from-indigo-100 to-purple-100 text-indigo-700 rounded-full text-sm hover:scale-105 transition-transform duration-200">
                {{ tech }}
              </span>
            </div>
            <div class="flex gap-2">
              <a-button type="primary" size="small" class="hover:scale-105 transition-transform duration-200">Live Demo</a-button>
              <a-button size="small" class="hover:scale-105 transition-transform duration-200">GitHub</a-button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const projects = ref([
  {
    id: 1,
    title: 'Gomi Kyoto',
    description: 'A web application for scheduling waste collection requests in Japan, integrating with JWNET system.',
    icon: '🗑️',
    technologies: ['VueJS', 'JavaScript', 'Tailwind CSS', 'JWNET API']
  },
  {
    id: 2,
    title: 'Employee Management System',
    description: 'Internal company project for managing employee information, time tracking, and project progress.',
    icon: '👥',
    technologies: ['VueJS', 'ExpressJS', 'Spring Boot', 'Java']
  },
  {
    id: 3,
    title: 'Portfolio Website',
    description: 'Personal portfolio website showcasing skills, experience, and projects with modern UI/UX.',
    icon: '💼',
    technologies: ['VueJS', 'TypeScript', 'Tailwind CSS', 'Ant Design']
  }
])
</script>
