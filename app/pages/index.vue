<template>
  <div>
    <p>Hello from the main page!</p>
  </div>
</template>

<script setup>
useSeoMeta({
  title: 'Main Page',
  description: 'This is a blog about Gsus',
  ogTitle: 'Main Page',
  twitterTitle: 'Main Page',
  twitterDescription: 'This is a blog about Gsus'
})

useHead({
  htmlAttrs: {
    lang: 'en'
  },
  link: [
    {
      rel: 'icon',
      type: 'image/png',
      href: '/favicon.png'
    }
  ]
})
</script>
