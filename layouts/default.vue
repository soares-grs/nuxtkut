<template>
    <div class="grid grid-rows-[auto,1fr,auto] min-h-screen">
      <header class="flex justify-around m-2 p-1 bg-white">
        <h1 class="text-xl font-bold text-[#ED2590]">Nuxtkut</h1>
        <div class="hidden md:flex gap-8">
          <p class="cursor-pointer">Início</p>
          <p class="cursor-pointer text-[#ED2590] font-semibold">Perfil</p>
          <p class="cursor-pointer">Comunidades</p>
          <p class="cursor-pointer">Jogos</p>
        </div>
      </header>
      <main class="bg-[#D9E6F7] overflow-auto p-4">
        <slot />
      </main>
    </div>
  </template>
  