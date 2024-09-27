<template>
  <div class="shadow-md rounded-lg overflow-hidden flex flex-col justify-between">
    <img :src="image" :alt="title" class="w-full h-48 object-cover"/>
    <div class="p-4">
      <h3 class="text-2xl sm:text-3xl font-semibold text-[#A97A13] mb-4">{{ title }}</h3>
      <p class="text-gray-500 text-justify mb-4">{{ description }}</p>
      <div class="flex justify-around items-center">
        <a :href="demoLink" target="_blank" class="p-2 hover:text-[#A97A13] icon"><img class="w-8" src="/static/images/website-click-svgrepo-com.svg" alt="git"></a>
        <a :href="codeLink" target="_blank" class="p-2 hover:text-[#A97A13] icon"><img class="w-8" src="/static/images/github-code-source-svgrepo-com.svg" alt="git"></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true
    },
    description: {
      type: String,
      required: true
    },
    image: {
      type: String,
      required: true
    },
    demoLink: {
      type: String,
      required: true
    },
    codeLink: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped>
</style>
