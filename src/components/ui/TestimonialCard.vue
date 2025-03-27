<script setup lang="ts">
    type TerimonialProps = {
        message: string;
        firstname: string;
        middlename: string;
        lastname: string
    };
    const props = defineProps < TerimonialProps > ()
</script>

<template>
    <div class="max-w-[25rem] p-5 italic relative">
        <span class="testimonial">&nbsp;</span>
        <div class="flex items-center justify-center flex-col gap-5">
            <div class="h-20 w-20">
                <img src="/public/avatar.png" class="h-full w-full">
            </div>
            <p class="text-center">
                {{ props . message }}
            </p>
            <div>
                ⭐⭐⭐⭐⭐
            </div>
            <p>
                {{ `${props . firstname} ${props . middlename}` }}
                <span class="text-gray-500">
                    {{ props . lastname }}
                </span>
            </p>
        </div>
    </div>
</template>


<style scoped>
    .grid span.testimonial::after {
        content: "’’";
        font-family: sans-serif;
        font-size: 5rem;
        font-weight: 900;
        position: absolute;
        right: 20px;
    }
</style>
