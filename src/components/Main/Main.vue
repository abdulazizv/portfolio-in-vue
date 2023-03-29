<template>
  <!-- main div -->
  <div class="wrapper__main container mx-auto flex flex-row pt-[120px] pb-[120px] min-h-screen justify-between">
    <!-- left div -->
    <div class="wrapper__main--left  max-w-[662px] w-full flex flex-col">
        <!-- article and buttons  -->
      <div class="intro ">
        <h1 class="font-bold text-[72px]  text-[#132238]">
          Hello,I'm Abdulaziz Bozorov
        </h1>
        <p class="text-[#556070] text-lg">
          I'm a <span class="text-[#132238]">Full stack Developer</span> based in Tashkent, Uzbekistan.
          I strives to build immersive and beautiful web sites through
          carefully crafted code and user-centric design.
        </p>
        <button class="btn bg-[#A53DFF] text-white font-semibold px-3 py-3 mt-[24px] rounded-lg hover:bg-[#bd8de7]">Say Hello!</button>
      </div>
      <div class="flex flex-row information__owner mt-10 gap-x-1 ">
        <div class="experience flex flex-col px-6 bg-[#EDD8FF] justify-center items-center">
            <h3 class="font-bold py-2 text-2xl">4,5 M.</h3>
            <p class="font-normal">experience</p>
        </div>
        <div class="project flex flex-col px-6 bg-[#EDD8FF] justify-center items-center">
            <h3 class="font-bold py-2 text-2xl">5 P</h3>
            <p class="font-normal">project completed</p>
        </div>
        <div class="client flex flex-col px-6 bg-[#EDD8FF] justify-center items-center">
            <h3 class="font-bold py-2 text-2xl">Five +</h3>
            <p class="font-normal">Happy Client</p>
        </div>
      </div>
    </div>

    <div class="bg-white-400 shadow-xl">
      <img src="https://picsum.photos/324" alt="">
    </div>
  </div>
</template>
<script>
export default {
  name: "Main",
};
</script>
<style scoped></style>
