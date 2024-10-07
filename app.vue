<template>
  <div>
    <NuxtRouteAnnouncer />
    <!--    NAVBAR   -->
    <header class="sticky top-0 z-50 flex justify-between items-center space-x-1 border-b bg-white p-4 shadow-md">
      <a class="text-3xl font-mono" href="">cartrader</a>
    </header>
    <!--    NAVBAR   -->

    <!--    HOME HERO   -->
    <div class="relative h-screen w-100 bg-no-repeat bg-cover bg-bottom bg-[url('images/super-car-heroImage.webp')]">
      <div class="z-10 absolute w-full h-full flex justify-center items-center">
        <div class="text-center w-1/2">
          <h1 class="text-8xl font-serif mb-10 text-white">Find Your Drive</h1>
          <!--    Home Search Bar   -->
          <div class="font-serif w-[1000px] text-2xl bg-white rounded-full flex justify-between overflow-hidden drop-shadow-2xl mx-auto">
            <input
              class="w-full py-3 px-4 text-2xl rounded-full focus:outline-none"
              type="text"
              placeholder="Search for city..."
            />
            <button class="px-10 bg-sky-500 text-white">Search</button>
          </div>
        </div>
      </div>
      <div class="z-1 absolute w-full h-full bg-black opacity-50"></div>
    </div>
    <!--    HOME HERO   -->
  </div>
</template>
