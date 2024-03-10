<script setup></script>

<template>
  <section class="flex flex-col gap-2 items-center">
    <header class="text-[#4B4B4B] text-lg">
        Comunidades
    </header>
    <div
    class="grid grid-cols-2 gap-3 w-auto bg-white rounded-md shadow-sm p-8"
    >
    <ProfileCommunity v-for="(community, index) in 6" :communityIndex="index"/>
    </div>
  </section>
</template>
