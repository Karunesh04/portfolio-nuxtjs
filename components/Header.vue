<template>
    <header class="hero">
        <nav class="flex sm:justify-between items-center">
            <NuxtLink class="w-24 cursor-pointer" to="/home"><img src="/static/images/K.png" alt="logo"></NuxtLink>
            <ul
                class="py-4 text-base sm:text-lg lg:text-xl font-bold text-gray-500 flex flex-wrap items-center justify-end gap-4 lg:gap-12">
                <li class="px-2 lg:px-4">
                    <NuxtLink active-class="text-[#A97A13]" to="/home">Home</NuxtLink>
                </li>
                <li class="px-2 lg:px-4">
                    <NuxtLink active-class="text-[#A97A13]" to="/about">About Me</NuxtLink>
                </li>
                <li class="px-2 lg:px-4">
                    <NuxtLink active-class="text-[#A97A13]" to="/skills">Skills</NuxtLink>
                </li>
                <li class="px-2 lg:px-4">
                    <NuxtLink active-class="text-[#A97A13]" to="/projects">Projects</NuxtLink>
                </li>
                <li class="px-4 lg:px-6 border-2 border-[#A97A13] hover:bg-[#A97A13] rounded-xl transition-all duration-300"
                    style="color:white;">
                    <NuxtLink to="/contact" class="block w-full h-full py-2">Contact</NuxtLink>
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