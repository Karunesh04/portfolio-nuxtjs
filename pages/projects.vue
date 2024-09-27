<template>
  <section id="projects" class="py-6 mb-16">
    <div class="container mx-auto">
      <h2 class="text-3xl sm:text-4xl lg:text-5xl font-bold text-[#A97A13] text-center mb-16">
        Projects
      </h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8">

        <!-- Project 1 -->
        <!-- <div class="shadow-md rounded-lg overflow-hidden flex flex-col justify-between">
          <img src="/static/images/project1.png" alt="Project Title" class="w-full h-48 object-cover" />
          <div class="p-4">
            <h3 class="text-2xl sm:text-3xl font-semibold text-[#A97A13] mb-4">Project Title</h3>
            <p class="text-gray-500 text-justify mb-4">
              This is a brief description of the project. It highlights the main features and technologies used in the
              project.
            </p>
            <div class="flex justify-around items-center">
              <a href="https://live-demo-link.com" target="_blank" class="p-2 hover:text-[#A97A13] icon">
                <img class="w-8" src="/static/images/website-click-svgrepo-com.svg" alt="Live Demo" />
              </a>
              <a href="https://github.com/project-repo" target="_blank" class="p-2 hover:text-[#A97A13] icon">
                <img class="w-8" src="/static/images/github-code-source-svgrepo-com.svg" alt="GitHub Code" />
              </a>
            </div>
          </div>
        </div> -->

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
