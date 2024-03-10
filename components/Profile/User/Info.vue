<template>
  <section class="bg-white flex flex-col gap-2 px-12 py-8 rounded-md shadow-md">
    <header class="p-4">
      <h1 class="text-xl">Boa tarde, Gabriel Soares</h1>
      <div class="flex flex-col">
        <p class="bg-[#EFF3F8] rounded-md shadow-sm p-2 text-sm">
          O jogo só acaba quando termina.
        </p>
      </div>
    </header>
    <div class="px-4 flex gap-6">
        <div class="flex flex-col items-start">
            <p class="text-lg">Fã</p>
            <div class="flex gap-1 items-center">
                <IconsStar class="text-[#FACF41] h-6 w-6"/>
                <p class="text-sm">10</p>
            </div>
        </div>
        <div class="flex flex-col items-start">
            <p class="text-lg">Confiável</p>
            <div class="flex gap-1 items-center">
                <IconsSmiley class="text-[#FACF41] h-6 w-6"/>
                <IconsSmiley class="text-[#FACF41] h-6 w-6"/>
            </div>
        </div>
        <div class="flex flex-col items-start">
            <p class="text-lg">Legal</p>
            <div class="flex gap-1 items-center">
                <IconsThumbs class="text-[#26CAFF] h-6 w-6"/>
                <IconsThumbs class="text-[#26CAFF] h-6 w-6"/>
                <IconsThumbs class="text-[#26CAFF] h-6 w-6"/>
            </div>
        </div>
    </div>
    <main>
        <ProfileUserQuality label="Relacionamento" value="Namorando"/>
        <ProfileUserQuality label="Aniversário" value="22 de Dezembro"/>
        <ProfileUserQuality label="Idade" value="21"/>
        <ProfileUserQuality label="Quem sou eu" value="Apenas um programador"/>
        <ProfileUserQuality label="Filhos" value="Ainda não"/>
        <ProfileUserQuality label="Sexo" value="Masculino"/>
        <ProfileUserQuality label="Fumo" value="Só charuto"/>
        <ProfileUserQuality label="Bebo" value="Não"/>
        <ProfileUserQuality label="Moro" value="em casa"/>
        <ProfileUserQuality label="País" value="Brasil"/>
        <ProfileUserQuality label="Cidade natal" value="Aracaju"/>
    </main>
  </section>
</template>
