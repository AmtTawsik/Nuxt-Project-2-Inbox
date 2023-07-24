<script setup>

</script>
<template>
    <div class="mx-4">
        <ol class="flex items-center w-full space-x-2 text-sm font-medium text-center text-gray-500 bg-white  sm:text-base">
            <li class="flex items-center">
                <span class="flex items-center justify-center w-5 h-5 mr-2 text-xs">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                        <path
                            d="M11.47 3.84a.75.75 0 011.06 0l8.69 8.69a.75.75 0 101.06-1.06l-8.689-8.69a2.25 2.25 0 00-3.182 0l-8.69 8.69a.75.75 0 001.061 1.06l8.69-8.69z" />
                        <path
                            d="M12 5.432l8.159 8.159c.03.03.06.058.091.086v6.198c0 1.035-.84 1.875-1.875 1.875H15a.75.75 0 01-.75-.75v-4.5a.75.75 0 00-.75-.75h-3a.75.75 0 00-.75.75V21a.75.75 0 01-.75.75H5.625a1.875 1.875 0 01-1.875-1.875v-6.198a2.29 2.29 0 00.091-.086L12 5.43z" />
                    </svg>
                </span>
                Home
                <svg aria-hidden="true" class="w-4 h-4 ml-2 sm:ml-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 5l7 7-7 7M5 5l7 7-7 7">
                    </path>
                </svg>
            </li>
            <li class="flex items-center">
                Users
                <svg aria-hidden="true" class="w-4 h-4 ml-2 sm:ml-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 5l7 7-7 7M5 5l7 7-7 7">
                    </path>
                </svg>
            </li>
            <li class="flex items-center">
                Profile
            </li>
        </ol>
        <h2 class="text-3xl font-semibold my-2">Profile</h2>
        <section class="grid grid-cols-12 gap-5">
            <div class="md:col-span-4 col-span-12">
                <Section1></Section1>
            </div>
            <div class="md:col-span-8 col-span-12">
                <Section2></Section2>
            </div>
        </section>
    </div>
</template>
