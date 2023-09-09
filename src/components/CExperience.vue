<template>
     <div class="bg-gray-700 px-2 py-4 rounded-lg border-4 border-gray-500 p-4 duration-500 transform hover:scale-105 zoomed">
        <div class="flex">
            <i class="material-icons text-3xl sm:text-3 xl md:text-4xl lg:text-4xl xl:text-4xl mt-1 sm:mt-1  md:mt-0 lg:mt-1 xl:mt-2  text-blue-400 mr-2 text-white">work</i>
            <div class=" mt-2 space-x-2 text-lg md:text-2xl lg:text-2xl xl:text-3xl font-bold text-white "> EXPERIENCE</div>
        </div>
        <div class="border-b border-gray-400 mx-2 my-3 px-2 w-30 "></div>

        <div class="ml-5">
            <div class="text-justify justify-center  items-center text-white text-2xl sm:text-md font-bold">
                Senior Staff (Full Stack Developer)
            </div>
            <div class="text-justify justify-center  items-center text-white  text-2xl sm:text-md font-bold">
                H.R.D Singapore PTE. LTD | April 2021 - Present
            </div>
            <div v-for="(item, i) in task" :key="i" class="flex items-center text-sm md:text-base" >
                <div class=" justify-center  items-center text-white text-lg">
                    <i class="material-icons text-sm md:text-sm text-black-400 mr-2 mt-1  text-white">fiber_manual_record</i>
                    {{ item.text }}
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
    import { ref} from 'vue';
    const task =ref(
        [
            {text:'Conducted training session for newly and internal hired employees regarding in web development.'},
            {text:'Designing and developing API with a logical structure, endpoints, request and response format, authentication methods, and error handling.'},
            {text:'Creating and maintaining a web system for in-house use involves designing, developing, and managing a web-based application that serves internal and external needs of the company.'},
            {text:'Conducted unit testing on server-side code components to ensure their accuracy, efficiency and adherence to specifications.'}
        ]
    )
</script>

<style>

</style>