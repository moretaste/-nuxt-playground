<template>
  <section class="relative max-w-5xl mx-auto pt-20 sm:pt-24 lg:pt-32">
    <h1 class="text-slate-900 font-extrabold text-4xl sm:text-5xl lg:text-6xl tracking-tight text-center dark:text-white" v-text="heading"></h1>
    <p class="mt-6 text-lg text-slate-600 text-center max-w-3xl mx-auto dark:text-slate-400" v-html="body"></p>
  </section>
</template>

<script>
export default {
  props: {
    heading: String,
    body: String
  }
}

</script>