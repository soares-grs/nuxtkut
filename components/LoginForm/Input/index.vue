<script setup>
defineProps({
    placeholder: {
        type: String
    }
})
</script>

<template>
    <input type="text" class="p-2 outline-none rounded-md shadow-sm w-full bg-[#EFF3F8] text-[#868686]" :placeholder="placeholder"/>
</template>