<template>
  <div class="pt-16">
    <section class="section-padding">
      <div class="container-custom">
        <div class="max-w-3xl mb-16">
          <h1 class="heading-1 mb-6">Blog</h1>
          <p class="text-xl text-gray-400">
            Thoughts on web development, Laravel, open source, and building quality software.
          </p>
        </div>

        <!-- Blog Posts Grid -->
        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
          <!-- Placeholder posts -->
          <article class="bg-gray-800/50 rounded-xl border border-gray-700/50 overflow-hidden group">
            <div class="aspect-video bg-gray-700/50 flex items-center justify-center text-gray-500">
              Blog Image
            </div>
            <div class="p-6">
              <span class="text-foxen-400 text-sm">Coming Soon</span>
              <h2 class="font-semibold text-lg mt-2 group-hover:text-foxen-400 transition-colors">
                Why We Chose Laravel for Everything
              </h2>
              <p class="text-gray-400 text-sm mt-2">
                A deep dive into why Laravel is our framework of choice for web applications.
              </p>
            </div>
          </article>

          <article class="bg-gray-800/50 rounded-xl border border-gray-700/50 overflow-hidden group">
            <div class="aspect-video bg-gray-700/50 flex items-center justify-center text-gray-500">
              Blog Image
            </div>
            <div class="p-6">
              <span class="text-foxen-400 text-sm">Coming Soon</span>
              <h2 class="font-semibold text-lg mt-2 group-hover:text-foxen-400 transition-colors">
                Building NutriPlan: Lessons from an Open Source Journey
              </h2>
              <p class="text-gray-400 text-sm mt-2">
                What we learned building and releasing an open source nutrition app.
              </p>
            </div>
          </article>

          <article class="bg-gray-800/50 rounded-xl border border-gray-700/50 overflow-hidden group">
            <div class="aspect-video bg-gray-700/50 flex items-center justify-center text-gray-500">
              Blog Image
            </div>
            <div class="p-6">
              <span class="text-foxen-400 text-sm">Coming Soon</span>
              <h2 class="font-semibold text-lg mt-2 group-hover:text-foxen-400 transition-colors">
                The Real Cost of Cheap Development
              </h2>
              <p class="text-gray-400 text-sm mt-2">
                Why investing in quality development pays off in the long run.
              </p>
            </div>
          </article>

          <article class="bg-gray-800/50 rounded-xl border border-gray-700/50 overflow-hidden group">
            <div class="aspect-video bg-gray-700/50 flex items-center justify-center text-gray-500">
              Blog Image
            </div>
            <div class="p-6">
              <span class="text-foxen-400 text-sm">Coming Soon</span>
              <h2 class="font-semibold text-lg mt-2 group-hover:text-foxen-400 transition-colors">
                UK Web Development: Why Local Matters
              </h2>
              <p class="text-gray-400 text-sm mt-2">
                The benefits of working with a UK-based development team.
              </p>
            </div>
          </article>

          <article class="bg-gray-800/50 rounded-xl border border-gray-700/50 overflow-hidden group">
            <div class="aspect-video bg-gray-700/50 flex items-center justify-center text-gray-500">
              Blog Image
            </div>
            <div class="p-6">
              <span class="text-foxen-400 text-sm">Coming Soon</span>
              <h2 class="font-semibold text-lg mt-2 group-hover:text-foxen-400 transition-colors">
                Open Source as a Business Strategy
              </h2>
              <p class="text-gray-400 text-sm mt-2">
                How open source can benefit both your business and the community.
              </p>
            </div>
          </article>
        </div>

        <!-- Newsletter -->
        <div class="mt-20 bg-gray-800/30 rounded-xl p-8 border border-gray-700/50 text-center">
          <h2 class="heading-3 mb-4">Stay Updated</h2>
          <p class="text-gray-400 mb-6">
            Subscribe to get notified when we publish new articles.
          </p>
          <form class="flex flex-col sm:flex-row gap-3 max-w-md mx-auto">
            <input 
              type="email" 
              placeholder="Enter your email" 
              class="flex-1 px-4 py-3 bg-gray-800 border border-gray-700 rounded-lg focus:border-foxen-500 focus:outline-none"
            >
            <button type="submit" class="btn-primary whitespace-nowrap">
              Subscribe
            </button>
          </form>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
useHead({
  title: 'Blog | Foxen Digital',
})
</script>
