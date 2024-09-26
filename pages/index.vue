<template>
    <div class="h-full w-[95vw] m-auto ">
        <Header />
        <!-- Main -->
        <main class="flex flex-col items-center justify-center text-center p-6 mt-8">
            <img class="w-40 h-40 shadow-xl shadow-[#A97A13] rounded-full mb-6" src="/assets/images/profile.png"
                alt="profile">
            <h2 class="text-2xl sm:text-3xl lg:text-6xl mt-5 font-bold text-[#A97A13] mb-4">
                Hello! I'm Karunesh :)
            </h2>

            <p class="mt-5 text-lg sm:text-xl lg:text-2xl text-gray-500 text-justify max-w-4xl leading-relaxed">
                Aspiring software developer with MERN stack expertise and experience in building full-stack
                applications.
                Skilled in data structures, algorithms, and a strong academic background. A team player, eager to
                contribute
                and grow in software development.
            </p>
            <a class="mt-16 inline-flex items-center gap-2 text-white text-lg bg-[#A97A13] p-4 rounded-2xl resume-button"
                href="https://drive.google.com/file/d/1ek3cMaZtCv-7KYPwGll-VMnp9_FW1ZII/view?usp=drive_link"
                target="_blank">
                <img class="icon w-8" src="/assets/images/file.png" alt="file">
                View My Resume
            </a>
        </main>
        <!-- About -->
        <section class="py-16 px-4 max-w-4xl mx-auto mt-6 ">
            <h2 class="text-3xl sm:text-4xl lg:text-5xl font-bold text-[#A97A13] text-center mb-8">
                About Me
            </h2>

            <p class="text-lg sm:text-xl lg:text-2xl text-gray-500 text-justify mb-6">
                Hello! I’m Karunesh, a passionate full-stack web developer with a strong interest in creating dynamic
                and user-friendly web applications. With a Master’s degree in Computer Applications, I have developed a
                solid foundation in both frontend and backend technologies.
            </p>

            <h3 class="text-2xl sm:text-3xl font-semibold text-[#A97A13] mb-4">
                My Journey
            </h3>
            <p class="text-lg sm:text-xl text-gray-500 text-justify mb-4">
                My journey into web development began with a curiosity about how websites work and a desire to bring
                ideas to life through code. Over the years, I have honed my skills in various programming languages and
                frameworks, including:
            </p>
            <ul class="list-disc list-inside text-lg sm:text-xl text-gray-500 mb-6">
                <li><strong>Frontend:</strong> HTML, CSS, JavaScript, React, Vue.js, Tailwind CSS</li>
                <li><strong>Backend:</strong> Node.js, Express, MongoDB, PHP, MySQL</li>
                <li><strong>Tools:</strong> Git, GitHub, Postman, Canva</li>
            </ul>

            <p class="text-lg sm:text-xl text-gray-500 mb-6">
                When I’m not coding, you can find me exploring the latest tech trends, working on personal projects, or
                contributing to open-source communities. I’m always open to new opportunities, collaborations, and
                learning experiences.
            </p>
            <p class="text-lg sm:text-xl text-gray-500">
                Feel free to reach out if you’d like to connect!
            </p>
        </section>
        <!-- Skills -->
        <section id="skills" class="py-10 max-w-4xl mx-auto text-gray-500">
            <div class="container mx-auto text-center">
                <h2 class="text-3xl sm:text-4xl lg:text-5xl font-bold text-[#A97A13] text-center mb-8">
                    Skills
                </h2>
                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-6">

                    <!-- Skill Item -->
                    <div class="flex flex-col items-center">
                        <img src="/assets/images/html-svgrepo-com.svg" alt="HTML" class="w-16 h-16 icon">
                        <p class="mt-2 text-lg font-semibold">HTML</p>
                    </div>

                    <div class="flex flex-col items-center">
                        <img src="/assets/images/css-svgrepo-com.svg" alt="CSS" class="w-16 h-16 icon">
                        <p class="mt-2 text-lg font-semibold">CSS</p>
                    </div>

                    <div class="flex flex-col items-center">
                        <img src="/assets/images/javascript-svgrepo-com.svg" alt="JavaScript" class="w-16 h-16 icon">
                        <p class="mt-2 text-lg font-semibold">JavaScript</p>
                    </div>

                    <div class="flex flex-col items-center">
                        <img src="/assets/images/react-svgrepo-com.svg" alt="React" class="w-16 h-16 icon">
                        <p class="mt-2 text-lg font-semibold">React</p>
                    </div>

                    <div class="flex flex-col items-center">
                        <img src="/assets/images/nodejs-icon-svgrepo-com.svg" alt="Node.js" class="w-16 h-16 icon">
                        <p class="mt-2 text-lg font-semibold">Node.js</p>
                    </div>

                    <div class="flex flex-col items-center">
                        <img src="/assets/images/mongo-svgrepo-com.svg" alt="MongoDB" class="w-16 h-16 icon">
                        <p class="mt-2 text-lg font-semibold">MongoDB</p>
                    </div>

                    <div class="flex flex-col items-center">
                        <img src="/assets/images/github-142-svgrepo-com.svg" alt="Git" class="w-16 h-16 icon">
                        <p class="mt-2 text-lg font-semibold">Git</p>
                    </div>

                    <div class="flex flex-col items-center">
                        <img src="/assets/images/tailwind-svgrepo-com.svg" alt="Tailwind" class="w-16 h-16 icon">
                        <p class="mt-2 text-lg font-semibold">Tailwind CSS</p>
                    </div>

                </div>
            </div>
        </section>

        <!-- Projects -->
        <!-- Contact -->
        <Footer />

    </div>
</template>


<script setup lang="ts">
definePageMeta({
    layout: "default",
})
</script>

<style scoped>
.resume-button {
    transition: transform 0.3s ease, background 0.3s ease;
}

.icon {
    transition: transform 0.3s ease;
}

.resume-button:hover {
    transform: scale(1.05);
    background: #916b12;
}

.icon:hover {
    transform: scale(1.1);
}
</style>
