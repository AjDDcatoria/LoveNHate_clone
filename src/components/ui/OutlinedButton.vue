<script setup lang="ts">
    type OutlinedButtonProps = {
        class ? : string;
    }
    const props = defineProps < OutlinedButtonProps > ()
</script>

<template>
    <button
        :class="[
            props.class,
            'border rounded-xl h-fit animation duration-300 ease-in-out text-white font-bolder text-xl px-20 py-10 text-black font-semibold text-sm tracking-[0.2rem] mt-10'
        ]">
        <slot />
    </button>
</template>
