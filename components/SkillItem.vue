<template>
  <div class="flex flex-col items-center">
    <img :src="src" :alt="alt" class="w-12 lg:w-16 icon" />
    <p class="mt-2 text-lg font-semibold">{{ name }}</p>
  </div>
</template>

<script>
export default {
  props: {
    src: String,
    alt: String,
    name: String,
  },
};
</script>


