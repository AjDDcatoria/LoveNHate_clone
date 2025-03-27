<script setup lang="ts">
    import TestimonialCard from './ui/TestimonialCard.vue';
</script>


<template>
    <div class="flex items-center justify-center flex-col gap-20 bg-zinc-900 text-white p-20">
        <h2 class="text-5xl font-bold text-center">Satisfied Customers</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3">
            <TestimonialCard 
                firstname="Mishmahig" 
                middlename="L." 
                lastname="Bahrain"
                message="Love your products, thanks also for the freebies." 
            />
            <TestimonialCard 
                firstname="Suqūr" 
                middlename="J." 
                lastname="Saudi Arabia"
                message="The cream is very very good Super high quality" 
            />
            <TestimonialCard 
                firstname="Suqūr" 
                middlename="J." 
                lastname="Saudi Arabia"
                message="The cream is very very good Super high quality" 
            />
            <TestimonialCard 
                firstname="Suqūr" 
                middlename="J." 
                lastname="Saudi Arabia"
                message="The cream is very very good Super high quality" 
            />
            <TestimonialCard 
                firstname="Suqūr" 
                middlename="J." 
                lastname="Saudi Arabia"
                message="The cream is very very good Super high quality" 
            />
        </div>
    </div>
</template>



