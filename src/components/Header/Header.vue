<template>
        <header class="fixed w-full  shadow-2xl  bg-[#FFFFFF]">
        <div class="wrapper h-[70px] sticky flex flex-row justify-between container mx-auto">
                <div class="logo flex items-center">
                    <div class="wrapper__logo bg-[#A53DFF] flex items-center justify-center rounded-3xl px-2 py-3">
                        <h1 class="text-white px-3 font-bold text-xl">A</h1>
                    </div> <h1 class="py-3 ml-1 text-[#132238] text-3xl font-bold">Abdulaziz</h1>
                </div>
                <ul class="flex flex-row items-center  hover:cursor-pointer hover:text-[#5a5151] max-w-[652px] ml-[160px] w-full justify-around text-lg font-semibold text-[#333333]">
                        <routerlink to="/" class="">Home</routerlink>
                        <routerlink to="/about">About</routerlink>
                        <routerlink to="/process">Process</routerlink>
                        <routerlink to="/portfolio">Portfolio</routerlink>
                        <routerlink to="/blog">Blog</routerlink>
                        <routerlink to="/services">Services</routerlink>
                    <button class="btn bg-[#A53DFF] text-lg font-bold px-3 py-2 text-white rounded-lg hover:ring-2 hover:outline-none">Contact</button>
                </ul>
        </div>
    </header>   
</template>
<script>
export default {
    name:'Header',
    data() {
        return {
        }
    },
}
</script>
<style>
    
</style>