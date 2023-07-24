<script setup>
import profile1 from '../assets/photo/profile1.png'
import ht from '../assets/photo/ht.png'
import li from '../assets/photo/li.png'
import xd from '../assets/photo/xd.png'
import fi from '../assets/photo/fi.png'
</script>

<template>
    <div class="p-5 border-2 shadow-lg rounded-lg mb-3">
        <img class="w-20 h-20 rounded-lg" :src="profile1" alt="">
        <h1 class="text-2xl font-bold my-2">Jese Leos</h1>
        <p class="flex items-center text-base text-gray-600">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 mr-1">
                <path fill-rule="evenodd"
                    d="M7.5 5.25a3 3 0 013-3h3a3 3 0 013 3v.205c.933.085 1.857.197 2.774.334 1.454.218 2.476 1.483 2.476 2.917v3.033c0 1.211-.734 2.352-1.936 2.752A24.726 24.726 0 0112 15.75c-2.73 0-5.357-.442-7.814-1.259-1.202-.4-1.936-1.541-1.936-2.752V8.706c0-1.434 1.022-2.7 2.476-2.917A48.814 48.814 0 017.5 5.455V5.25zm7.5 0v.09a49.488 49.488 0 00-6 0v-.09a1.5 1.5 0 011.5-1.5h3a1.5 1.5 0 011.5 1.5zm-3 8.25a.75.75 0 100-1.5.75.75 0 000 1.5z"
                    clip-rule="evenodd" />
                <path
                    d="M3 18.4v-2.796a4.3 4.3 0 00.713.31A26.226 26.226 0 0012 17.25c2.892 0 5.68-.468 8.287-1.335.252-.084.49-.189.713-.311V18.4c0 1.452-1.047 2.728-2.523 2.923-2.12.282-4.282.427-6.477.427a49.19 49.19 0 01-6.477-.427C4.047 21.128 3 19.852 3 18.4z" />
            </svg>
            Front-end Developer
        </p>
        <p class="flex items-center text-base text-gray-600">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 mr-1">
                <path fill-rule="evenodd"
                    d="M11.54 22.351l.07.04.028.016a.76.76 0 00.723 0l.028-.015.071-.041a16.975 16.975 0 001.144-.742 19.58 19.58 0 002.683-2.282c1.944-1.99 3.963-4.98 3.963-8.827a8.25 8.25 0 00-16.5 0c0 3.846 2.02 6.837 3.963 8.827a19.58 19.58 0 002.682 2.282 16.975 16.975 0 001.145.742zM12 13.5a3 3 0 100-6 3 3 0 000 6z"
                    clip-rule="evenodd" />
            </svg>
            San Francisco, USA
        </p>
        <p class="text-base text-gray-600 mt-3">
            Email address:
        </p>
        <p class="font-semibold">yourname@flowbite.com</p>
        <p class="text-base text-gray-600 mt-3">
            Home address:
        </p>
        <p class="font-semibold">92 Miles Drive, Newark, NJ 07103, California,</p>
        <p class="font-semibold">United States of America</p>
        <p class="text-base text-gray-600 mt-3">
            Phone Number:
        </p>
        <p class="font-semibold">+00 123 456 789 / +12 345 678</p>
        <p class="font-bold mt-3">
            Software Skill:
        </p>
        <div class="flex items-center gap-2 mt-1">
            <img class="w-12" :src="ht" alt="">
            <img class="w-12" :src="xd" alt="">
            <img class="w-12" :src="li" alt="">
            <img class="w-12" :src="fi" alt="">
        </div>
    </div>
    <div class="p-5 border-2 shadow-lg rounded-lg mb-3">
        <h3 class="text-xl font-bold mb-3">Skills</h3>
        <div class="flex flex-wrap gap-2">
            <p class="flex whitespace-nowrap text-green-900 bg-green-50 font-semibold w-fit px-3 py-1 rounded-lg">Brand
                Design</p>
            <p class="flex whitespace-nowrap text-green-900 bg-green-50 font-semibold w-fit px-3 py-1 rounded-lg">Logo
                Design</p>
            <p class="flex whitespace-nowrap text-green-900 bg-green-50 font-semibold w-fit px-3 py-1 rounded-lg">Mobile App
                Design</p>
            <p class="flex whitespace-nowrap text-green-900 bg-green-50 font-semibold w-fit px-3 py-1 rounded-lg">UI Design
            </p>
            <p class="flex whitespace-nowrap text-green-900 bg-green-50 font-semibold w-fit px-3 py-1 rounded-lg">React
                Developer</p>
            <p class="flex whitespace-nowrap text-green-900 bg-green-50 font-semibold w-fit px-3 py-1 rounded-lg">Wordpress
            </p>
            <p class="flex whitespace-nowrap text-green-900 bg-green-50 font-semibold w-fit px-3 py-1 rounded-lg">Sketch</p>
            <p class="flex whitespace-nowrap text-green-900 bg-green-50 font-semibold w-fit px-3 py-1 rounded-lg">Figma</p>
            <p class="flex whitespace-nowrap text-green-900 bg-green-50 font-semibold w-fit px-3 py-1 rounded-lg">
                Prototyping</p>
            <p class="flex whitespace-nowrap text-green-900 bg-green-50 font-semibold w-fit px-3 py-1 rounded-lg">Database
            </p>
        </div>
    </div>
    <div class="p-5 border-2 shadow-lg rounded-lg">
        <h3 class="text-xl font-bold mb-3">Hobbies</h3>
        <div class="flex flex-wrap gap-2">
            <p class="flex whitespace-nowrap text-violet-900 bg-violet-50 font-semibold w-fit px-3 py-1 rounded-lg">Football</p>
            <p class="flex whitespace-nowrap text-violet-900 bg-violet-50 font-semibold w-fit px-3 py-1 rounded-lg">Dogs</p>
            <p class="flex whitespace-nowrap text-violet-900 bg-violet-50 font-semibold w-fit px-3 py-1 rounded-lg">Gaming</p>
            <p class="flex whitespace-nowrap text-violet-900 bg-violet-50 font-semibold w-fit px-3 py-1 rounded-lg">Movies</p>
            <p class="flex whitespace-nowrap text-violet-900 bg-violet-50 font-semibold w-fit px-3 py-1 rounded-lg">Travelling</p>
            <p class="flex whitespace-nowrap text-violet-900 bg-violet-50 font-semibold w-fit px-3 py-1 rounded-lg">Surf</p>
            <p class="flex whitespace-nowrap text-violet-900 bg-violet-50 font-semibold w-fit px-3 py-1 rounded-lg">Ice Skating</p>
            <p class="flex whitespace-nowrap text-violet-900 bg-violet-50 font-semibold w-fit px-3 py-1 rounded-lg">The Witcher</p>
        </div>
    </div>
</template>

