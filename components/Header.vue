<template>
    <header class="hero">
        <nav class="flex sm:justify-between items-center">
            <NuxtLink  class="w-24 cursor-pointer" to="/"><img src="/assets/images/K.png" alt="logo"></NuxtLink>
            <ul
                class="py-4 text-base sm:text-lg lg:text-xl font-bold text-gray-500 flex flex-wrap items-center justify-end gap-4 lg:gap-12">
                <li class="px-2 lg:px-4">
                    <NuxtLink to="/about" active-class="text-[#A97A13]">About Me</NuxtLink>
                </li>
                <li class="px-2 lg:px-4">
                    <NuxtLink to="/skills" active-class="text-[#A97A13]">Skills</NuxtLink>
                </li>
                <li class="px-2 lg:px-4">
                    <NuxtLink to="/projects" active-class="text-[#A97A13]">Projects</NuxtLink>
                </li>
                <li class="px-4 lg:px-6 hover:bg-[#A97A13] rounded-lg" style="color:white;">
                    <NuxtLink to="/contact">Contact</NuxtLink>
                </li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
li:hover {
    color: #A97A13;
    cursor: pointer;
    transition-duration: 1s;
}
</style>