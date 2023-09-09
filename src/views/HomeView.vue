<template>
  <div class="container mx-auto"  >
    <div  >
      <div class="flex flex-col sm:flex-col md:flex-col lg:flex-row xl:flex-row ">
        <div class=" w-4/4  sm:w-4/4 md:w-4/4 lg:w-1/4 p-4  flex justify-center items-center bg-gray-950 ">
          <CPictureVue />
        </div>
        <div class="w-4/4 sm:w-4/4  md:w-4/4 lg:w-3/4 p-4 bg-gray-900  ">
          <div class="text-3xl sm:text-4xl  md:text-6xl font-semibold mb-2 text-gray-300"><b>JOHN LLOYD MUNCAL</b></div>

            <div class="flex flex-col md:flex-row">
            <!-- Email Section -->
            <div class="flex items-center ml-2 text-lg md:text-xl mb-2 md:mb-0">
              <i class="material-icons text-xl md:text-2xl  text-white">email</i>
              <b class="text-white ">: jlloydmuncal@gmail.com</b>
            </div>
            <!-- Phone Section -->
            <div class="flex items-center ml-2 text-lg md:text-xl">
              <i class="material-icons text-xl md:text-2xl  text-white">phone</i>
              <b class="text-white ">: +639106829490</b>
            </div>
          </div>
          
          <div class="border-b border-gray-400 mx-2 my-3 px-2 "></div>
          <CProfile />
        </div>
      </div>
      <div>
        <div class="flex flex-col sm:flex-col md:flex-col lg:flex-row xl:flex-row  ">
            <div class="w-4/4  sm:w-4/4 md:w-4/4 lg:w-1/4 px-4  order-2 sm:order-2 md:order-2 lg:order-1 xl:order-1 items-center 
            bg-gray-950  sm:bg-gray-900   md:bg-gray-900 lg:bg-gray-950 xl:bg-gray-950">
              <div class="border-b border-gray-400 mx-2 my-3 px-2 "></div>
                <CExpertiseVue/>
            </div>
            <div class="w-4/4 sm:w-4/4  md:w-4/4 lg:w-3/4 px-4 order-1 bg-gray-900  ">
              <div class="border-b border-gray-400 mx-2 my-3 px-2  "></div>
                <CExperienceVue />
              <div class="border-b border-gray-400 mx-2 my-3 px-2 "></div>
                <CEducation/>
              <div class="border-b border-gray-400 mx-2 my-3 px-2 "></div>
                <CLanguage />
              <div class="border-b border-gray-400 mx-2 my-3 px-2 "></div>
                <CHobbiesVue/>
            </div>
        </div>
      </div>
    </div>
    <footer  >
      <div class="flex flex-col sm:flex-col md:flex-col lg:flex-row xl:flex-row">
        <div class=" w-4/4  sm:w-4/4 md:w-4/4 lg:w-1/4 p-4  flex justify-center items-center  bg-gray-950    sm:bg-gray-900   md:bg-gray-900 lg:bg-gray-950 xl:bg-gray-950">
       
        </div>
        <div class="container mx-auto text-center w-4/4 sm:w-4/4  md:w-4/4 lg:w-3/4 p-4 bg-gray-900    sm:bg-gray-950   md:bg-gray-950 lg:bg-gray-900 xl:bg-gray-900 ">
            <p class="text-sm lg:text-base text-white">&copy; 2023 JL-Muncal.</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup>

  import CEducation from "../components/CEducation.vue";
  import CExperienceVue from "../components/CExperience.vue";
  import CExpertiseVue from "../components/CExpertise.vue";
  import CHobbiesVue from "../components/CHobbies.vue";
  import CLanguage from "../components/CLanguage.vue";
  import CPictureVue from "../components/CPicture.vue";
  import CProfile from "../components/CProfile.vue";
</script>
<style scoped>
</style>
