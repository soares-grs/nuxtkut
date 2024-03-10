<script setup>
defineProps({
    friendIndex: {
        
    }
})
</script>

<template>
   <div class="flex flex-col justify-center items-center">
        <img
          class="h-10 w-10 rounded-full"
          src="~assets/cute-dog.jpg"
          alt="User Avatar"
        />
        <p class="mt-2 text-sm text-[#4B4B4B]">Cute Dog {{ friendIndex }}</p>
      </div>
</template>