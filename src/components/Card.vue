<script setup>

defineProps({
    bg: {
        type: String,
        default: 'bg-gray-100'
    }
})
</script>

<template>
    <div :class="`${bg}`" class=" p-6 rounded-lg shadow-md">
            <slot>

            </slot>
    </div>
</template>