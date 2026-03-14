<template>
  <div class="bg-white rounded-xl shadow-md overflow-hidden hover:scale-105 transform transition">
    <img :src="image" :alt="title" class="w-full h-48 object-cover">
    <div class="p-4">
      <h4 class="text-xl font-semibold mb-2">{{ title }}</h4>
      <p class="text-gray-600">{{ description }}</p>
      <a :href="link" class="text-blue-600 font-semibold mt-2 inline-block hover:underline">View Project</a>
    </div>
  </div>
</template>

<script setup>
defineProps({
  title: String,
  description: String,
  link: String,
  image: String
})
</script>