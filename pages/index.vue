<template>
    <main class="flex flex-col items-center justify-center text-center p-4 my-8">
        <img class="w-40 h-40 shadow-xl shadow-[#A97A13] rounded-full mb-6" src="/static/images/profile.png"
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
        <a class="mt-16 inline-flex items-center gap-2 text-white text-lg bg-[#A97A13] p-4 rounded-xl resume-button"
            href="https://drive.google.com/file/d/1ek3cMaZtCv-7KYPwGll-VMnp9_FW1ZII/view?usp=drive_link"
            target="_blank">
            <img class="icon w-8" src="/static/images/file.png" alt="file">
            View My Resume
        </a>
    </main>
</template>



<style scoped>
.resume-button {
    transition: transform 0.3s ease, background 0.3s ease;
}

.resume-button:hover {
    transform: scale(1.05);
}
</style>
