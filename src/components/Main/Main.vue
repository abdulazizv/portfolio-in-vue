<template>
  <!-- main div -->
  <div class="wrapper__main flex flex-row mt-[120px] ">
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
      <div class="flex flex-row information__owner mt-10">
        <div class="experience flex flex-col bg-[#EDD8FF]">
            <h3 class="font-bold px-2 py-3">4,5 M.</h3>
            <p class="font-normal px-2 py-3">experience</p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Main",
};
</script>
<style scoped></style>
