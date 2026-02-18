<template>
  <div class="pt-16">
    <section class="section-padding">
      <div class="container-custom">
        <!-- Header -->
        <div class="mb-12">
          <NuxtLink to="/projects" class="text-gray-400 hover:text-white transition-colors mb-4 inline-flex items-center gap-2">
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7" />
            </svg>
            Back to Projects
          </NuxtLink>
          <h1 class="heading-1 mb-4">NutriPlan</h1>
          <p class="text-xl text-gray-400 max-w-3xl">
            A smarter approach to meal planning and nutrition tracking, designed with UK users and metabolic health in mind.
          </p>
        </div>

        <!-- Screenshot -->
        <div class="bg-gray-800 rounded-xl p-4 border border-gray-700 mb-12">
          <img src="/img/recipes-ipad.png" alt="NutriPlan recipe view">
        </div>

        <!-- Content -->
        <div class="grid lg:grid-cols-3 gap-12">
          <div class="lg:col-span-2 space-y-8">
            <div>
              <h2 class="heading-2 mb-4">The Problem</h2>
              <p class="text-gray-400">
                Most nutrition apps are US-centric, ad-supported, and treat blood glucose management as an afterthought. Users serious about metabolic health deserve better tools that understand their needs.
              </p>
            </div>

            <div>
              <h2 class="heading-2 mb-4">Our Solution</h2>
              <ul class="space-y-3">
                <li class="flex items-start gap-3 text-gray-400">
                  <svg class="w-5 h-5 text-foxen-500 mt-0.5 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                  </svg>
                  UK-first approach with British food databases and measurements
                </li>
                <li class="flex items-start gap-3 text-gray-400">
                  <svg class="w-5 h-5 text-foxen-500 mt-0.5 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                  </svg>
                  Blood glucose and lipid profile tracking built in from day one
                </li>
                <li class="flex items-start gap-3 text-gray-400">
                  <svg class="w-5 h-5 text-foxen-500 mt-0.5 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                  </svg>
                  No ads, no tracking, full data ownership
                </li>
                <li class="flex items-start gap-3 text-gray-400">
                  <svg class="w-5 h-5 text-foxen-500 mt-0.5 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                  </svg>
                  Open source and self-hostable for complete control
                </li>
              </ul>
            </div>

            <div>
              <h2 class="heading-2 mb-4">Features</h2>
              <div class="grid sm:grid-cols-2 gap-4">
                <div class="bg-gray-800/50 rounded-lg p-4 border border-gray-700/50">
                  <h3 class="font-semibold mb-2">Meal Planning</h3>
                  <p class="text-gray-400 text-sm">Plan meals in advance with nutritional information and calorie tracking.</p>
                </div>
                <div class="bg-gray-800/50 rounded-lg p-4 border border-gray-700/50">
                  <h3 class="font-semibold mb-2">Blood Glucose Tracking</h3>
                  <p class="text-gray-400 text-sm">Monitor glucose levels and see how meals affect your readings.</p>
                </div>
                <div class="bg-gray-800/50 rounded-lg p-4 border border-gray-700/50">
                  <h3 class="font-semibold mb-2">Lipid Profile</h3>
                  <p class="text-gray-400 text-sm">Track cholesterol and other blood markers over time.</p>
                </div>
                <div class="bg-gray-800/50 rounded-lg p-4 border border-gray-700/50">
                  <h3 class="font-semibold mb-2">UK Food Database</h3>
                  <p class="text-gray-400 text-sm">British foods with accurate nutritional data and measurements.</p>
                </div>
              </div>
            </div>
          </div>

          <!-- Sidebar -->
          <div class="space-y-6">
            <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700/50">
              <h3 class="font-semibold mb-4">Tech Stack</h3>
              <div class="flex flex-wrap gap-2">
                <span class="px-3 py-1 bg-gray-700 rounded-full text-sm">Laravel</span>
                <span class="px-3 py-1 bg-gray-700 rounded-full text-sm">Livewire</span>
                <span class="px-3 py-1 bg-gray-700 rounded-full text-sm">Tailwind CSS</span>
                <span class="px-3 py-1 bg-gray-700 rounded-full text-sm">PostgreSQL</span>
              </div>
            </div>

            <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700/50">
              <h3 class="font-semibold mb-4">Status</h3>
              <p class="text-emerald-400 text-sm mb-4">Active Development</p>
              <p class="text-gray-400 text-sm">
                NutriPlan is under active development with regular updates and new features being added.
              </p>
            </div>

            <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700/50">
              <h3 class="font-semibold mb-4">Links</h3>
              <div class="space-y-3">
                <a href="https://github.com/MrKareth/nutriplan" target="_blank" class="flex items-center gap-2 text-foxen-400 hover:text-foxen-300">
                  <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                    <path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0024 12c0-6.63-5.37-12-12-12z"/>
                  </svg>
                  View on GitHub
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
useHead({
  title: 'NutriPlan | Foxen Digital',
})
</script>
