<script setup lang="ts">
import ProductCard from './ui/ProductCard.vue';
</script>

<template>
    <div class="flex flex-col gap-10 items-center p-10">
        <h2 class="text-6xl font-bold">PRODUCTS</h2>
        <div class="h-[0] w-20 border"></div>
        <div class="h-15 rounded-xl w-full max-w-[38rem] bg-gray-100 flex text-sm">
            <button class="w-[15rem] text-gray-500">All</button>
            <input type="text" placeholder="Search Gallery Item..."
                class="border-l border-gray-400 h-full w-full pl-5 focus:outline-none focus:ring-0 text-gray-400">
        </div>
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-5">
            <ProductCard title="THOR (Mango Berries)" image="/public/product.jpg"/>
            <ProductCard title="VENOM (Honeydew/Melon)" image="/public/product.jpg"/>
            <ProductCard title="Hulk (Honeydew/Melon)" image="/public/product.jpg"/>
            <ProductCard title="Spider (Lychee)" image="/public/product.jpg"/>
            <ProductCard title="Apolo (Lychee)" image="/public/product.jpg"/>
            <ProductCard title="Vintage (Peach)" image="/public/product.jpg"/>
            <ProductCard title="Poseidon (Peach)" image="/public/product.jpg"/>
            <ProductCard title="Kong (Berries)" image="/public/product.jpg"/>
        </div>
        <button class="bg-black text-white py-4 px-10 text-sm hover:scale-110 transition duration-300 ease-in-out">
            READ OUR REVIEWS
        </button>
    </div>
</template>
