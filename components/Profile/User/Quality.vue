<script setup>
defineProps({
    label: {
        type: String
    },
    value: {
        type: String
    }
})
</script>

<template>
    <div class="px-4 mt-2 flex items-center gap-2">
        <p class="text-md text-[#B4AEAE]">{{ label }}: </p>
        <p class="text-md text-[#4B4B4B]">{{ value }}</p>
    </div>
</template>