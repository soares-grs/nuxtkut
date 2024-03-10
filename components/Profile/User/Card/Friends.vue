<script setup></script>

<template>
  <section class="flex flex-col gap-2 items-center">
    <header class="text-[#4B4B4B] text-lg">
        Amigos
    </header>
    <div
    class="grid grid-cols-2 gap-3 w-auto bg-white rounded-md shadow-sm p-8"
    >
    <ProfileFriend v-for="(friend, index) in 6" :friendIndex="index"/>
    </div>
  </section>
</template>
