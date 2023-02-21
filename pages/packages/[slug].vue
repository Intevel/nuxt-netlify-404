<template>
  <div>
    Dynamic NuxtPage
    Slug: {{  slug }}
  </div>
</template>

<script setup>
const availableSlugs = ["test", "nuxt", "nuxt2"]
const route = useRoute();
const slug = route.params.slug;

// if (!availableSlugs.includes(slug)) {
//   throw createError({ statusCode: 404, statusMessage: "Not found"})
// }
</script>