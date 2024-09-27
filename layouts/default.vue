<template>
    <div class="h-full w-[95vw] m-auto">
        <Header />

        <main>
            <slot />
        </main>
        
        <Footer />
    </div>
</template>

<script setup>
console.log("default layout applied")
</script>