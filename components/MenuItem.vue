<script setup>

</script>

<template>
    <div class="mt-2 flex divide-x divide-gray-400 dark:divide-neutral-700 ">
            <router-link to="/"
                class="flex flex-col items-center w-full py-2 text-neutral-400 dark:text-neutral-500 md:py-4 lg:py-6 xl:py-8"
                active-class="dark:!text-white !text-black">
                <span><IconsHome class="h-5 w-5 md:h-7 md:w-7 lg:h-12 lg:w-12" /></span>
                <span>Start</span>
            </router-link>
            <router-link to="/pricing"
            class="flex flex-col items-center w-full py-2 text-neutral-400 dark:text-neutral-500 md:py-4 lg:py-6 xl:py-8"
                active-class="dark:!text-white !text-black">
                <span><IconsAbout class="h-5 w-5 md:h-7 md:w-7 lg:h-12 lg:w-12" /></span>
                <span>Über uns</span>
            </router-link>
            <router-link to="/about-me"
            class="flex flex-col items-center w-full py-2 text-neutral-400 dark:text-neutral-500 md:py-4 lg:py-6 xl:py-8"
                active-class="dark:!text-white !text-black">
                <span><IconsImpressum class="h-20 w-20 md:h-7 md:w-7 lg:h-12 lg:w-12" /></span>
                <span>Über uns</span>
            </router-link>
    </div>
    
</template>
