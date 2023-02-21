<template>
  <div class="main max-w-7xl mx-auto my-8 p-4 sm:p-6 md:p-8 bg-slate-50 rounded-lg p-6 dark:bg-slate-800 dark:highlight-white/5">
    <header>
      <Darkmode />
      <Navigation />
    </header>
    <main>
      <slot name="main" />
    </main>
    <footer>
      <slot name="footer" />
    </footer>
  </div>
</template>

<script setup lang="ts">
useHead({
  title: 'Nuxt playground',
  meta: [
    { name: 'description', content: 'Play and learn with nuxt3' }
  ],
  htmlAttrs: {
    class: 'w-full h-full'
  },
  bodyAttrs: {
    class: 'antialiased text-slate-500 dark:text-slate-400 bg-white dark:bg-slate-900 w-full h-full'
  },
})
</script>
