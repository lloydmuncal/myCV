<template>
    <div class="bg-gray-700 px-2 py-4 rounded-lg border-4 border-gray-500 p-4 duration-500 transform hover:scale-105 zoomed">
        <div class="flex">
            <i class="material-icons text-3xl sm:text-3 xl md:text-4xl lg:text-4xl xl:text-4xl mt-1 sm:mt-1  md:mt-0 lg:mt-1 xl:mt-2  text-blue-400 mr-2 text-white">sentiment_very_satisfied</i>
            <div class=" mt-2 space-x-2 text-lg md:text-xl lg:text-2xl xl:text-3xl font-bold text-white"> HOBBIES</div>
         </div>
        <div class="border-b border-gray-400 mx-2 my-3 px-2 w-30 "></div>
        <div class="ml-4 grid grid-cols-1 sm:grid-cols-3  md:grid-cols-4 lg:grid-cols-4  xl:grid-cols-2 gap-3 ">
            <div class="text-justify flex " v-for="(item, i) in hobbies">
                <i class="material-icons text-xl sm:text-2xl md:text-3xl lg:text-4xl xl:text-4xl text-blue-400 mb-2 sm:mb-0 mr-2 text-white">{{ `${item.icon}`}}</i>
                <div class="text-lg sm:text-xl md:text-lg lg:text-xl xl:text-xl font-semibold text-white">{{ item.text }}</div>
            </div>
        </div>
    </div>
</template>

<script setup>
import {ref} from 'vue'
const hobbies =ref([
    {text:'MUSIC',icon:'music_note'},
    {text:'Travel',icon:'flight'},
    {text:'Food',icon:'restaurant'},
    {text:'Movie',icon:'movie_creation'},
])

</script>

<style>

</style>