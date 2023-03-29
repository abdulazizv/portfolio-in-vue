<template>
  <div
    class="about h-[600px] w-full container mx-auto bg-white shadow-2xl mb-24 flex flex-row justify-between items-center "
  >
    <div class="photo flex justify-center items-center flex-col ml-[50px]">
      <img src="../../assets/Rectangle 30.png" alt="" />
      <div class="social__media--logos shadow-2xl bg-white -mt-8 flex flex-row gap-4 max-w-[264px] list-none px-7 py-6">
      <li class=""><a href="https://facebook.com" class=""><img src="../../assets/facebook.svg" alt="fb"></a></li>
      <li class=" "><a href="https://webstorm.com"><img src="../../assets/worldwebb.svg" alt="worldweb"></a></li>
      <li class=""><a class="bg-[#A53DFF]" href="https://instagram.com/abdulaziz"><img src="../../assets/instagram.svg" alt="worldweb"></a></li>
      <li class=""><a href="https://linkedin.com"><img src="../../assets/linkedin.svg" alt="in"></a></li>
      <li class=" "><a href="https://behance.com"><img src="../../assets/bee.svg" alt="behance"></a></li>
    </div>
    </div>
    <div class="about__info w-[60%]">
      <p class="jobprofession text-[#132238] font-semibold text-[38px] mb-4">
        I am Node.js Backend and Vue.js Frontend Developer. 
      </p>
      <p class="text-[18px] font-thin mb-2">
        I design and develop services for customers specializing creating
        stylish, modern websites, web services and online stores. My passion is
        to design digital user experiences.
      </p>
      <p class="text-[#87909D] text-[18px]">
        I design and develop services for customers specializing creating
        stylish, modern websites, web services.
      </p>
      <div class="btn flex flex-row gap-5 mt-10">
      <button class="btn text-white bg-[#A53DFF] px-6 py-3 font-semibold font-sans rounded-md text-[16px] hover:bg-white hover:text-[#A53DFF] hover:border border-1 hover:border-[#A53DFF]">My Project</button>
      <button class="btn flex flex-row gap-2 bg-white px-6 py-3 text-[#A53DFF] border-[#A53DFF] border-2 rounded-md hover:bg-[#A53DFF] hover:text-white"><img src="../../assets/Vector.svg" alt=""> Download CV</button>
    </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "About",
};
</script>
<style lang="css"></style>
