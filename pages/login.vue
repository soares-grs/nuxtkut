<script setup>
definePageMeta({
    layout: "login"
})
</script>

<template>
    <div class="h-full flex justify-center items-center">
        <main class="flex gap-6 m-8">
            <img
              class="hidden md:block h-[400px] w-[500px] shadow-md"
              src="~assets/login-splash.png"
              alt="People laughing and havin fun connected on Nuxtkut"
            />
            <LoginForm/>
        </main>
    </div>
</template>
