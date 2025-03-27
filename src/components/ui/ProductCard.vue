<script setup lang="ts">
type ProductCartProps = {
    title: string;
}
const props = defineProps<ProductCartProps>();

</script>

<template>
    <div class="bg-white h-fit">
        <div class="relative group border border-gray-300">
            <image src="/public/product.jpg" alt=""
                class="h-[20rem] w-full object-cover transition-all"/>
            <div
                class="absolute inset-0 bg-black opacity-0 group-hover:opacity-50 transition-opacity animation duration-300 ease-in">
            </div>
            <button
                class="absolute top-1/2 right-[23%] transform -translate-x-1/2 -translate-y-1/2 text-white opacity-0 group-hover:opacity-100  bg-zinc-600/60 hover:bg-orange-500 transition animation duration-200 ease-in p-3 rounded-full">
                <img src="/public/searchplus.svg" class="h-7">
            </button>
            <button
                class="absolute top-1/2 left-[40%] transform -translate-x-1/2 -translate-y-1/2 text-white opacity-0 group-hover:opacity-100  bg-zinc-600/60 hover:bg-orange-500 transition animation duration-200 ease-in p-3 rounded-full">
                <img src="/public/searchplus.svg" class="h-7">
            </button>
        </div>
        <div class="p-5">
            <p class="font-semibold text-xl">{{ props.title }}</p>
        </div>
    </div>
</template>
