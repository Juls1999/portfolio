<template>
  <section id="projects" class="py-20 px-6 max-w-6xl mx-auto">
    <h3 class="text-3xl font-bold mb-12 text-center">My Projects</h3>
    <div class="grid gap-8 md:grid-cols-2 lg:grid-cols-3">
      <ProjectCard
        v-for="project in projects"
        :key="project.title"
        :title="project.title"
        :description="project.description"
        :link="project.link"
        :image="project.image"
      />
    </div>
  </section>
</template>

<script setup>
import ProjectCard from './ProjectCard.vue'

const projects = [
  {
    title: "Project One",
    description: "A brief description of what this project is about.",
    link: "#",
    image:"https://placehold.co/600x400/000000/FFFFFF/png"
  },
  {
    title: "Project Two",
    description: "Another project description goes here.",
    link: "#",
    image:"https://placehold.co/600x400/000000/FFFFFF/png"
  },
  {
    title: "Project Three",
    description: "Another project description goes here.",
    link: "#",
    image:"https://placehold.co/600x400/000000/FFFFFF/png"
  }
]
</script>