<script setup></script>

<template>
  <div class="bg-pink-300 h-max">
    <div class="relative m-auto max-w-5xl pt-5">
      <nav class="flex justify-between items-center">
        <div class="flex items-center gap-5 pb-2">
          <div class="w-24 h-24 bg-white rounded-xl flex items-center justify-center">
            <img src="/Vector.png" alt="Logo" />
          </div>
          <span class="main-title text-4xl">Муза </span>
        </div>
        <div class="flex items-center justify-between gap-8">
          <a href="#" class="coursor-pointer text-lg font-black text-white">Главная</a>
          <a href="#" class="coursor-pointer text-lg font-black text-white">Преподаватели</a>
          <a href="#" class="coursor-pointer text-lg font-black text-white drop-shadow-md"
            >О студии</a
          >
          <a href="#" class="coursor-pointer text-lg font-black text-white">Контакты</a>
        </div>
        <div class="flex items-center gap-10">
          <span class="text-lg font-black text-white">+7 901 745-39-29</span>
          <a href="#" class="coursor-pointer"><img src="/telegram.png" alt="telegram" /></a>
        </div>
      </nav>
      <header class="w-auto h-[660px] flex">
        <div class="mt-[40px] flex flex-col items-start justify-center h-full w-4/6 gap-12">
          <h1 class="text-5xl font-black text-white drop-shadow-md">Посадим на шпагат любую</h1>
          <p class="text-4xl font-black text-white drop-shadow-md">
            Студия растяжки в центре Москвы для тех, уто хочет красивое тело
          </p>
          <button
            class="coursor-pointer hover:opacity-80 hover:transition bg-gradient-to-b from-red-500 from-10% to-white-500 rounded-full text-3xl font-black text-white py-5 px-2 flex align-center justify-center"
          >
            Пробное занятие
          </button>
        </div>
        <img
          width="900px"
          src="/straching-woman.png"
          alt="woman"
          class="absolute left-[155px] top-[80px]"
        />
      </header>
    </div>
    <div
      class="h-[198px] w-full bg-gradient-to-r from-[#FDDFDF] from-10% to-pink-300 flex justify-center items-center"
    >
      <h1 class="text-5xl font-black text-black">Твоё красивое тело - наш приоритет</h1>
    </div>
    <div class="h-[950px]">
      <div class="m-auto max-w-5xl min-h-full grid grid-rows-2 justify-items-stretch">
        <img class="absolute" src="/straching-woman-2.png" alt="">
        <div
          class=" w-[360px] h-[280px] bg-white rounded-[40px] shadow-md  justify-self-end flex items-center "
        >
         <span class="text-5xl font-black text-black px-10">1 пробное занятие - 300 рублей</span> 
        </div>
        <div
          class="relative w-[360px] h-[280px] bg-white rounded-[40px] shadow-md text-5xl font-black text-black justify-self-start flex items-center "
        >
         <span class="text-5xl font-black text-black px-20">Запишись к нам на занятие</span> 
        </div>
      </div>
    </div>
  </div>
</template>

bg-[url('/straching-woman-2.png')] bg-top bg-no-repeat

<style scoped>
</style>
