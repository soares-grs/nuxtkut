<script setup>

</script>

<template>
    <div class="flex flex-col gap-4 p-4 w-[350px] md:w-[270px] rounded-md shadow-md bg-white items-center">
        <h1 class="text-[#ED2590] mb-6 font-semibold text-xl">Acesse o Nuxtkut</h1>
        <LoginFormInput
            placeholder="E-mail"
        />
        <LoginFormInput
            placeholder="Senha"
        />
        <div class="flex flex-col gap-2 w-full">
            <LoginFormButtonEntrar/>
            <LoginFormButtonCriar/>
        </div>
        <p class="text-[#ED2590] underline text-sm cursor-pointer">Esqueci a minha senha</p>
    </div>
</template>