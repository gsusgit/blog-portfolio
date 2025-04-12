<template>
  <nav class="font-mono">
    <ul class="flex space-x-4">
      <li>
        <nuxt-link to="/" class="link" active-class="active">Main</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/about" class="link" active-class="active">
          About
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="/blog" class="link" active-class="active">
          Blog
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="/projects" class="link" active-class="active">
          Projects
        </nuxt-link>
      </li>
    </ul>
  </nav>
</template>

<style scoped>
.link {
  @apply p-1 hover:font-semibold hover:bg-black hover:text-white;
}
.active {
  @apply font-semibold;
}
</style>
