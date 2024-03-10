<script setup>

</script>

<template>
    <main class="grid lg:grid-cols-3 grid-rows-subgrid gap-8 md:gap-6 md:grid-rows-1 mt-8">
        <ProfileUserCard/>
        <ProfileUserInfo/>
        <div class="flex flex-col gap-4 md:flex-row md:justify-center md:items-center md:gap-10 lg:flex-col">
            <ProfileUserCardFriends/>
            <ProfileUserCardCommunities/>
        </div>
    </main>
</template>
