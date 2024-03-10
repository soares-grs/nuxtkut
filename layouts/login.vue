<template>
    <div class="grid grid-rows-[auto,1fr,auto] min-h-screen">
      <header class="flex justify-around m-2 p-1 bg-white">
        <h1 class="text-xl font-bold text-[#ED2590]">Nuxtkut</h1>
        <div class="flex gap-8">
          <p>Sobre o Nuxtkut</p>
          <p>Centro de segurança</p>
        </div>
      </header>
      <main class="bg-[#D9E6F7] overflow-auto p-4">
        <slot />
      </main>
      <footer class="bg-white p-4 text-center text-[#ED2590] text-sm">
        Todos os direitos reservados
      </footer>
    </div>
  </template>
  