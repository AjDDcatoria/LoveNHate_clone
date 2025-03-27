<script setup lang="ts">
    import OutlinedButton from './ui/OutlinedButton.vue';
</script>

<template>
    <div class="hero px-10 h-fit">
        <section
            class="flex items-center justify-center flex-col lg:flex-row text-white gap-[7rem] min-h-[48rem] py-20">
            <div class="flex items-center jusfity-center h-[35rem]">
                <img src="/public/flavorProduct.webp" class="h-full w-full object-contain">
            </div>
            <div class="max-w-full lg:max-w-[38rem] flex flex-col items-center lg:items-start w-full">
                <div class="right">
                    <h3 class="font-bold text-7xl text-[#D39E80]">FLAVOR</h3>
                    <p class="text-2xl text-brown-200 text-[#83766E]">CHOOSE YOUR VERSION</p>
                    <p class="mt-5 text-[#BDBDBD]">
                        Each café is also carefully designed to incorporate a welcoming and
                        relaxed social setting to complete every customer visit.
                    </p>
                    <div class="grid grid-cols-2 grid-rows-[repeat(2,130px)] gap-3">
                        <OutlinedButton class="py-5 border-[#EBD69B] border-2 hover:border-[#81775E9F] hover:bg-[#45423AFF]">
                            <div class="h-full w-full gap-3 flex items-start lg:items-center flex-col lg:flex-row">
                                <img src="/public/apple.png" alt="" class="h-10">
                                <span>Fruits</span>
                            </div>
                        </OutlinedButton>
                        <OutlinedButton class="py-5 border-[#6AAEF5] border-2 hover:border-[#586F87B3] hover:bg-[#184474FF]">
                            <div class="h-full w-full gap-3 flex items-start lg:items-center flex-col lg:flex-row">
                                <img src="/public/icecream.png" alt="" class="h-10">
                                <span>Cream</span>
                            </div>
                        </OutlinedButton>
                        <OutlinedButton class="py-5 border-[#03DBFF] border-2 hover:border-[#49767EFF] hover:bg-[#20464CFF]">
                            <div class="h-full w-full gap-3 flex items-start lg:items-center flex-col lg:flex-row">
                                <img src="/public/box.png" alt="" class="h-10">
                                <span>Mentol</span>
                            </div>
                        </OutlinedButton>
                        <OutlinedButton class="py-5 border-[#DAA000] border-2 hover:border-[#605535FF] hover:bg-[#504420FF]">
                            <div class="h-full w-full gap-3 flex items-start lg:items-center flex-col lg:flex-row">
                                <img src="/public/cookie.png" alt="" class="h-10">
                                <span>Pastry</span>
                            </div>
                        </OutlinedButton>
                    </div>
                </div>
                <button
                    class="bg-[#D39E80] text-white px-10 py-3 font-semibold text-sm tracking-[0.2rem] mt-16 hover:scale-110 transition duration-300 ease-in-out">
                    VIEW ALL
                </button>
            </div>
        </section>
    </div>
</template>
