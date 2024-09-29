<template>
  <section id="skills" class="py-6 max-w-4xl mx-auto mb-8 md:mb-32 lg:mb-20 text-gray-500">
    <div class="container mx-auto text-center">
      <h2 class="text-3xl sm:text-4xl lg:text-5xl font-bold text-[#A97A13] text-center mb-4 sm:mb-8 md:mb-12 lg:mb-16">
        Skills
      </h2>
      <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-6 md:gap-10 lg:gap-20">
        <SkillItem
          v-for="(skill, index) in skills"
          :key="index"
          :src="skill.src"
          :alt="skill.alt"
          :name="skill.name"
        />
      </div>
    </div>
  </section>
</template>

<script>
import SkillItem from '~/components/SkillItem.vue';

export default {
  components: {
    SkillItem,
  },
  data() {
    return {
      skills: [
        { src: '/static/images/html-svgrepo-com.svg', alt: 'HTML', name: 'HTML' },
        { src: '/static/images/css-svgrepo-com.svg', alt: 'CSS', name: 'CSS' },
        { src: '/static/images/java-svgrepo-com.svg', alt: 'Java', name: 'Java' },
        { src: '/static/images/javascript-svgrepo-com.svg', alt: 'JavaScript', name: 'JavaScript' },
        { src: '/static/images/tailwind-svgrepo-com.svg', alt: 'Tailwind CSS', name: 'Tailwind CSS' },
        { src: '/static/images/nodejs-icon-svgrepo-com.svg', alt: 'Node.js', name: 'Node.js' },
        { src: '/static/images/react-svgrepo-com.svg', alt: 'React', name: 'React' },
        { src: '/static/images/nextjs-fill-svgrepo-com.svg', alt: 'Next.js', name: 'Next.js' },
        { src: '/static/images/vue-9-logo-svgrepo-com.svg', alt: 'Vue', name: 'Vue' },
        { src: '/static/images/nuxt-svgrepo-com.svg', alt: 'Nuxt.js', name: 'Nuxt.js' },
        { src: '/static/images/mongo-svgrepo-com.svg', alt: 'MongoDB', name: 'MongoDB' },
        { src: '/static/images/github-142-svgrepo-com.svg', alt: 'Git', name: 'Git' },
      ],
    };
  },
};
</script>

