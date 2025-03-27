<script setup>
import Banner from './components/Banner.vue';
import Flavor from './components/Flavor.vue';
import Header from './components/Header.vue';
import Hero from './components/Hero.vue';
import Products from './components/Products.vue';
import ReviewSection from './components/ReviewSection.vue';
import SatisfiedCustomers from './components/SatisfiedCustomers.vue';
</script>

<template>
    <div class="h-screen flex flex-col overflow-y-scroll bg-gray-50">
            <!-- Banner -->
            <Banner />
            <!-- Header -->
            <Header/>
            <!-- Hero -->
            <Hero/>
            <!-- Review section -->
            <ReviewSection/>
            <!-- Flavor -->
            <Flavor/>
            <!-- Products -->
             <Products/>
            <!-- Satisfied Customers -->
             <SatisfiedCustomers/>
            <!-- TODO Footer -->
    </div>
</template>