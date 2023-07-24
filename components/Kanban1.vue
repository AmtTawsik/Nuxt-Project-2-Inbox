<script setup>
import { onMounted } from 'vue'
import { initModals } from 'flowbite'
import p1 from '../assets/photo/kanban/p1.jpg'


onMounted(() => {
    initModals();
})
</script>

<template>
    <div class=''>
        <h1 class='text-2xl font-bold mb-5'>To Do</h1>
        <section class='px-4 pt-4 border rounded-lg shadow-md mb-3'>
            <div class='font-bold flex justify-between'>
                <h4>Change Charts JavaScript</h4>
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                    <path
                        d="M21.731 2.269a2.625 2.625 0 00-3.712 0l-1.157 1.157 3.712 3.712 1.157-1.157a2.625 2.625 0 000-3.712zM19.513 8.199l-3.712-3.712-8.4 8.4a5.25 5.25 0 00-1.32 2.214l-.8 2.685a.75.75 0 00.933.933l2.685-.8a5.25 5.25 0 002.214-1.32l8.4-8.4z" />
                    <path
                        d="M5.25 5.25a3 3 0 00-3 3v10.5a3 3 0 003 3h10.5a3 3 0 003-3V13.5a.75.75 0 00-1.5 0v5.25a1.5 1.5 0 01-1.5 1.5H5.25a1.5 1.5 0 01-1.5-1.5V8.25a1.5 1.5 0 011.5-1.5h5.25a.75.75 0 000-1.5H5.25z" />
                </svg>
            </div>
            <p class='my-3 text-gray-600'>In _variables.scss on line 672 you define $table_variants. Each instance of
                "color-level"
                needs to be changed to "shift-color".
            </p>
            <div class='flex justify-between items-center'>
                <div class="flex mb-5 -space-x-4">
                    <img class="w-10 h-10 border-2 border-white rounded-full "
                        src="https://flowbite.com/docs/images/people/profile-picture-5.jpg" alt="" />
                    <img class="w-10 h-10 border-2 border-white rounded-full "
                        src="https://flowbite.com/docs/images/people/profile-picture-2.jpg" alt="" />
                    <img class="w-10 h-10 border-2 border-white rounded-full "
                        src="https://flowbite.com/docs/images/people/profile-picture-3.jpg" alt="" />
                </div>
                <p
                    class="bg-blue-100 text-blue-800 text-sm font-bold -mt-2.5 px-2.5 py-0.5 rounded  border-blue-400 w-fit">
                    5 days left</p>
            </div>
        </section>

        <section class='px-4 pt-4 border rounded-lg shadow-md mb-3'>
            <div class='font-bold flex justify-between'>
                <h4>Change Charts JavaScript</h4>
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                    <path
                        d="M21.731 2.269a2.625 2.625 0 00-3.712 0l-1.157 1.157 3.712 3.712 1.157-1.157a2.625 2.625 0 000-3.712zM19.513 8.199l-3.712-3.712-8.4 8.4a5.25 5.25 0 00-1.32 2.214l-.8 2.685a.75.75 0 00.933.933l2.685-.8a5.25 5.25 0 002.214-1.32l8.4-8.4z" />
                    <path
                        d="M5.25 5.25a3 3 0 00-3 3v10.5a3 3 0 003 3h10.5a3 3 0 003-3V13.5a.75.75 0 00-1.5 0v5.25a1.5 1.5 0 01-1.5 1.5H5.25a1.5 1.5 0 01-1.5-1.5V8.25a1.5 1.5 0 011.5-1.5h5.25a.75.75 0 000-1.5H5.25z" />
                </svg>
            </div>
            <img class='mt-4 rounded-md' :src="p1" alt="" />
            <p class='my-3 text-gray-600'>Change home psge for Dashboard.</p>
            <div class='flex justify-between items-center'>
                <div class="flex mb-5 -space-x-4">
                    <img class="w-10 h-10 border-2 border-white rounded-full "
                        src="https://flowbite.com/docs/images/people/profile-picture-5.jpg" alt="" />
                    <img class="w-10 h-10 border-2 border-white rounded-full "
                        src="https://flowbite.com/docs/images/people/profile-picture-2.jpg" alt="" />
                    <img class="w-10 h-10 border-2 border-white rounded-full "
                        src="https://flowbite.com/docs/images/people/profile-picture-3.jpg" alt="" />
                </div>
                <p
                    class="bg-blue-100 text-blue-800 text-sm font-bold -mt-2.5 px-2.5 py-0.5 rounded  border-blue-400 w-fit">
                    7 days left</p>
            </div>
        </section>

        <section class='px-4 pt-4 border rounded-lg shadow-md mb-3'>
            <div class='font-bold flex justify-between'>
                <h4>Change Charts JavaScript</h4>
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                    <path
                        d="M21.731 2.269a2.625 2.625 0 00-3.712 0l-1.157 1.157 3.712 3.712 1.157-1.157a2.625 2.625 0 000-3.712zM19.513 8.199l-3.712-3.712-8.4 8.4a5.25 5.25 0 00-1.32 2.214l-.8 2.685a.75.75 0 00.933.933l2.685-.8a5.25 5.25 0 002.214-1.32l8.4-8.4z" />
                    <path
                        d="M5.25 5.25a3 3 0 00-3 3v10.5a3 3 0 003 3h10.5a3 3 0 003-3V13.5a.75.75 0 00-1.5 0v5.25a1.5 1.5 0 01-1.5 1.5H5.25a1.5 1.5 0 01-1.5-1.5V8.25a1.5 1.5 0 011.5-1.5h5.25a.75.75 0 000-1.5H5.25z" />
                </svg>
            </div>
            <p class='my-3 text-gray-600'>In _variables.scss on line 672 you define $table_variants. Each instance of
                "color-level"
                needs to be changed to "shift-color".
            </p>
            <div class='flex justify-between items-center'>
                <div class="flex mb-5 -space-x-4">
                    <img class="w-10 h-10 border-2 border-white rounded-full "
                        src="https://flowbite.com/docs/images/people/profile-picture-5.jpg" alt="" />
                    <img class="w-10 h-10 border-2 border-white rounded-full "
                        src="https://flowbite.com/docs/images/people/profile-picture-2.jpg" alt="" />
                    <img class="w-10 h-10 border-2 border-white rounded-full "
                        src="https://flowbite.com/docs/images/people/profile-picture-3.jpg" alt="" />
                </div>
                <p
                    class="bg-blue-100 text-blue-800 text-sm font-bold -mt-2.5 px-2.5 py-0.5 rounded  border-blue-400 w-fit">
                    22 days left</p>
            </div>
        </section>
        <section>

            <!-- Modal toggle -->
            <button data-modal-target="defaultModal1" data-modal-toggle="defaultModal1"
                class="block text-gray-600 font-bold w-full border-dashed border-2 border-gray-600 rounded-lg px-5 py-2.5 text-center"
                type="button">
                <span class="flex justify-center">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                        stroke="currentColor" class="w-6 h-6">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M12 4.5v15m7.5-7.5h-15" />
                    </svg>
                    Add another Card
                </span>
            </button>

            <!-- Main modal -->
            <div id="defaultModal1" tabindex="-1" aria-hidden="true"
                class="fixed top-0 left-0 right-0 z-50 hidden w-full p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-modal md:h-full">
                <div class="relative w-full h-full max-w-2xl md:h-auto">
                    <!-- Modal content -->
                    <div class="relative bg-white rounded-lg shadow ">
                        <form class="w-11/12 mx-auto">
                            <div class="mb-6">
                                <label for="default-input"
                                    class="block mb-2 text-sm font-medium text-gray-900 ">Default
                                    Task Name</label>
                                <input type="text" id="default-input"
                                    class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5  ">
                            </div>
                            <div class="mb-6">
                                <label for="default-input"
                                    class="block mb-2 text-sm font-medium text-gray-900 ">Default
                                    Enter a description</label>
                                <textarea rows="5" id="default-input"
                                    class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5  "></textarea>
                            </div>

                            <label for=""></label>
                            <div class="flex items-center justify-center w-full">
                                <label for="dropzone-file"
                                    class="flex flex-col items-center justify-center w-full h-64 border-2 border-gray-300 border-dashed rounded-lg cursor-pointer bg-gray-50 hover:bg-gray-100 ">
                                    <div class="flex flex-col items-center justify-center pt-5 pb-6">
                                        <svg aria-hidden="true" class="w-10 h-10 mb-3 text-gray-400" fill="none"
                                            stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                d="M7 16a4 4 0 01-.88-7.903A5 5 0 1115.9 6L16 6a5 5 0 011 9.9M15 13l-3-3m0 0l-3 3m3-3v12">
                                            </path>
                                        </svg>
                                        <p class="mb-2 text-sm text-gray-500 "><span
                                                class="font-semibold">Click to upload</span> or drag and drop</p>
                                        <p class="text-xs text-gray-500 ">SVG, PNG, JPG or GIF (MAX.
                                            800x400px)</p>
                                    </div>
                                    <input id="dropzone-file" type="file" class="hidden" />
                                </label>
                            </div>

                        </form>
                        <div
                            class="flex items-center p-6 space-x-2  border-gray-200 rounded-b ">
                            <button data-modal-hide="defaultModal1" type="button"
                                class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center ">I
                                Submit</button>
                            <button data-modal-hide="defaultModal1" type="button"
                                class="text-gray-500 bg-white hover:bg-gray-100 focus:ring-4 focus:outline-none focus:ring-blue-300 rounded-lg border border-gray-200 text-sm font-medium px-5 py-2.5 hover:text-gray-900 focus:z-10 ">Decline</button>
                    </div>
                </div>
            </div>
        </div>

    </section>
</div></template>