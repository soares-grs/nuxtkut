<script setup>
defineProps({
    communityIndex: {
        
    }
})
</script>

<template>
   <div class="flex flex-col justify-center items-center">
        <img
          class="h-10 w-10 rounded-md shadow-md"
          src="~assets/cute-dog.jpg"
          alt="User Avatar"
        />
        <p class="mt-2 text-sm text-[#4B4B4B]">Dog Community {{ communityIndex }}</p>
      </div>
</template>