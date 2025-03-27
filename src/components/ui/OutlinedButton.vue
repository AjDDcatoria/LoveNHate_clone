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
            'border rounded-xl w-full h-full flex animation duration-300 ease-in-out font-bolder px-5 text-white text-2xl font-semibold mt-10'
        ]">
        <slot />
    </button>
</template>
