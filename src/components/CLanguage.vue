<template>
    <div class="bg-gray-700 px-2 py-4 rounded-lg border-4 border-gray-500 p-4 duration-500 transform hover:scale-105 zoomed">
        <div class="flex">
            <i class="material-icons text-3xl sm:text-3 xl md:text-4xl lg:text-4xl xl:text-4xl mt-1 sm:mt-1  md:mt-0lu lg:mt-1 xl:mt-2  text-be-400 mr-2 text-white">language</i>
            <div class=" mt-2 space-x-2 text-lg md:text-xl lg:text-2xl xl:text-3xl font-bold text-white"> Language</div>
        </div>
       <div class="border-b border-gray-400 mx-2 my-3 px-2 w-30 "></div>
       <div class="ml-4 grid grid-cols-1 sm:grid-cols-3  md:grid-cols-4 lg:grid-cols-4  xl:grid-cols-2 gap-3">
            <div class="text-justify text-white text-xl">
                   <i class="material-icons text-xs md:text-sm text-black-400 mr-2 mt-1 ">fiber_manual_record</i>
                   {{ 'ENGLISH' }}
            </div>
            <div class="text-justify text-white text-xl">
                   <i class="material-icons text-xs md:text-sm text-black-400 mr-2 mt-1 ">fiber_manual_record</i>
                   {{ 'TAGALOG' }}
            </div>
        </div>
   </div>
</template>

<script>
    export default {
        
    }
</script>

<style>

</style>