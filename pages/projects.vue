<template>
  <section id="projects" class="py-6 mb-16">
    <div class="container mx-auto">
      <h2 class="text-3xl sm:text-4xl lg:text-5xl font-bold text-[#A97A13] text-center mb-16">
        Projects
      </h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8">

        <!-- Project 1 -->
        <ProjectCard title="EduConnect"
          description="A comprehensive platform built with the MERN stack (MongoDB, Express, React, Node.js) to connect students, educators, and institutions, facilitating online learning and interaction in a unified environment."
          image="/images/project1.png" demoLink="https://project1-demo-link.com"
          codeLink="https://github.com/Karunesh04/Learning-Management-System" />

        <!-- Project 2 -->
        <ProjectCard title="Portfolio"
          description="Developed using HTML, CSS, and JavaScript, this site showcases my skills, projects, and achievements in web development, with sections like About Me, Skills, Projects, and Contact Info."
          image="/images/project2.png" demoLink="https://karunesh04.netlify.app/"
          codeLink="https://github.com/Karunesh04/personalPortfolio" />

        <!-- Project 3 -->
        <ProjectCard title="Tindog"
          description="A fun, responsive Tinder clone for dogs, built using HTML, CSS, and Bootstrap. It allows dog owners to create profiles for their pets, including pictures, breed, age, and traits, to connect with other dog owners."
          image="/images/project3.png" demoLink="https://tinderwebsite.netlify.app/"
          codeLink="https://github.com/Karunesh04/Tindog" />
      </div>
    </div>
  </section>
</template>

<script>
import ProjectCard from '~/components/ProjectCard.vue'

export default {
  components: {
    ProjectCard
  }
}
</script>
