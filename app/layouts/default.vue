<template>
  <div class="container mx-auto max-w-2xl">
    <header class="flex justify-between items-center mt-5">
      <div>
        <nuxt-link to="/" class="text-3xl font-bold p-2 logo">Gsus</nuxt-link>
      </div>
      <navbar></navbar>
    </header>
    <main class="px-2 py-12 font-mono">
      <slot />
    </main>
  </div>
</template>

<script setup>
useHead({
  titleTemplate: '%s - Gsus',
  link: [
    {
      rel: 'preconnect',
      href: 'https://fonts.googleapis.com'
    },
    {
      rel: 'stylesheet',
      href: 'https://fonts.googleapis.com/css2?family=Audiowide&display=swap',
      crossorigin: ''
    }
  ]
})
</script>

<style scoped>
.logo {
  font-family: 'Audiowide', sans-serif;
}
</style>
