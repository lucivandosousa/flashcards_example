<template>
  <header class="flex justify-between items-center px-8 py-4 shadow">
    <img src="./assets/img/logo-laranja-estudie 1.png" alt="">
    <div class="cursor-pointer">
      <img src="./assets/img/Hambuguer.svg" alt="">
    </div>
  </header>
  <main class="px-8 py-4">
    <p class="mb-2">Filtrar flashcards:</p>
    <div class="grid grid-cols-2 gap-2 mb-2">
      <input type="text" placeholder="Todos os flashcards" class="bg-slate-200 p-1 rounded text-[12px] h-8">
      <input type="text" placeholder="Matérias" class="bg-slate-200 p-1 rounded text-[12px] h-8">
      <input type="text" placeholder="Conteúdos" class="bg-slate-200 p-1 rounded text-[12px] h-8">
      <input type="text" placeholder="Tópico específico 1" class="bg-slate-200 p-1 rounded text-[12px] h-8">
      <input type="text" placeholder="Tópico específico 2" class="bg-slate-200 p-1 rounded text-[12px] h-8">
      <button class="bg-red-600 text-white p-1 rounded font-bold h-8">Limpar filtros</button>
    </div>

    <div class="flex gap-1 flex-wrap mb-8">
      <p class="text-nowrap">Filtros selecionados: </p>
      <div class="flex gap-1 bg-slate-200 rounded justify-center items-center">
        <span class="text-nowrap">Todos os flashcards</span>
        <img src="./assets/img/X circle.svg">
      </div>
      <div class="flex gap-1 bg-slate-200 rounded justify-center items-center">
        <span class="text-nowrap">Biologia</span>
        <img src="./assets/img/X circle.svg">
      </div>
      <div class="flex gap-1 bg-slate-200 rounded justify-center items-center">
        <span class="text-nowrap">História</span>
        <img src="./assets/img/X circle.svg">
      </div>
    </div>

    <div class="mb-2 p-1 bg-slate-200 rounded flex justify-between items-center">
      <p>Evolução dos últimos flashcards:</p>
      <div class="flex gap-1">
        <div class="rounded-full h-3 w-3 bg-slate-400"></div>
        <div class="rounded-full h-3 w-3 bg-slate-400"></div>
        <div class="rounded-full h-3 w-3 bg-slate-400"></div>
        <div class="rounded-full h-3 w-3 bg-slate-400"></div>
        <div class="rounded-full h-3 w-3 bg-slate-400"></div>
      </div>
    </div>

    <div class="rounded border border-slate-200 h-96 relative">
      <div class="bg-orange-500 rounded-t p-2 text-white">
        <p class="text-2xl">Flashcards 04453</p>
        <p class="text-sm">História - Mundo Pós Guerra</p>
      </div>
      <div class="flex justify-center items-center h-[calc(100%-96px)]">
        <p class="font-bold text-center">O que foi a Guerra fria e qual foi sua relação com a Segunda Guerra Mundial?</p>
      </div>
      <div class="absolute bottom-0 w-full flex justify-between p-2 border-t border-slate-200">
        <button class="bg-orange-500 text-white p-1 rounded">Ver resposta</button>
        <button class="flex justify-center items-center gap-1"><span><img src="./assets/img/Journal.svg"></span>Criar anotações</button>
      </div>
    </div>
  </main>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>