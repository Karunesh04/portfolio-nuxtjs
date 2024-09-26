<template>
    <div class="h-full w-[95vw] m-auto ">
        <header class="hero">
            <nav class="flex sm:justify-between items-center p-4">
                <img class="w-24" src="/assets/images/K.png" alt="logo">
                <ul
                    class="text-base sm:text-lg lg:text-xl font-bold text-gray-500 flex flex-wrap items-center gap-6 lg:gap-12">
                    <li class="px-2 lg:px-4">About Me</li>
                    <li class="px-2 lg:px-4">Skills</li>
                    <li class="px-2 lg:px-4">Projects</li>
                    <li class="px-4 lg:px-6 hover:bg-[#A97A13] rounded-lg" style="color:white;">
                        Contact</li>
                </ul>
            </nav>

        </header>
        <!-- Main -->
        <main class="flex flex-col items-center justify-center text-center p-6">
            <img class="w-40 h-40 shadow-xl shadow-[#A97A13] rounded-full mb-6" src="/assets/images/profile.png"
                alt="profile">
            <h2 class="text-2xl sm:text-3xl lg:text-6xl mt-5 font-bold text-[#A97A13] mb-4">
                Hello! I'm Karunesh :)
            </h2>

            <p class="mt-5 text-base sm:text-lg lg:text-xl text-gray-600 max-w-2xl leading-relaxed">
                Aspiring software developer with MERN stack expertise and experience in building full-stack
                applications.
                Skilled in data structures, algorithms, and a strong academic background. A team player, eager to
                contribute
                and grow in software development.
            </p>
            <a class="mt-16 resume-button"
                href="https://drive.google.com/file/d/1ek3cMaZtCv-7KYPwGll-VMnp9_FW1ZII/view?usp=drive_link"
                target="_blank">
                <img class="resume-icon" src="/assets/images/file.png" alt="file">
                Resume
            </a>
        </main>
        <!-- Skills -->
        <section class="flex items-center just text-center">
            <h2 class="text-2xl sm:text-3xl lg:text-6xl mt-5 font-bold text-[#A97A13] mb-4">Skills</h2>
        </section>
        <footer class="sticky top-full flex items-center text-gray-500 border-t-2 border-gray-500">
            <img class="w-20" src="/assets/images/K.png" alt="logo">
            <p class="text-sm sm:text-base lg:text-lg font-medium ml-4">
                &copy; 2024 Karunesh -
                <a class="text-blue-400" target="_blank" href="https://karunesh04.netlify.app/">@karufolio</a>
            </p>
            <div class="ml-auto mr-4 flex justify-center gap-4">
                <a target="_blank" href="https://www.linkedin.com/in/karunesh04/">
                    <img class="w-8" src="/assets/images/linkedin-svgrepo-com.svg" alt="">
                </a>
                <a target="_blank" href="https://github.com/Karunesh04">
                    <img class="w-8" src="/assets/images/github-142-svgrepo-com.svg" alt="">
                </a>
            </div>
        </footer>

    </div>
</template>


<script setup lang="ts"></script>

<style scoped>
li:hover {
    color: #A97A13;
    cursor: pointer;
    transition-duration: 1s;
}

/* Style for the button */
.resume-button {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    text-decoration: none;
    font-size: 1rem;
    background: #A97A13;
    padding: 12px 15px;
    border-radius: 10px 12px;
    transition: transform 0.3s ease;
}

/* Style for the image icon */
.resume-icon {
    width: 1.5rem;
    transition: transform 0.3s ease;
}

/* Zoom effect on hover */
.resume-button:hover {
    transform: scale(1.1);
}

/* Optional: Zoom effect for the icon separately */
.resume-icon:hover {
    transform: scale(1.2);
}
</style>