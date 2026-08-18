<script setup>
</script>

<template>
<div class="min-h-screen px-5 pt-4 bg-[#F9F9F9]">
  <!-- back button & info button serta menunya -->
  <div class="flex justify-between">
    <div class="bg-[#EFEFEF] rounded-full w-12 h-12 grid place-items-center">
      <img src="/public/back.svg">
    </div>
    <div class="bg-[#EFEFEF] rounded-full w-12 h-12 grid place-items-center">
      <img src="/public/info.svg" alt="informasi">
    </div>
  </div>

  <!-- section header isi logo, filter buttons -->
  <section class="pt-8">
    <div>
      <img width="65%" src="/public/new-logo.svg" alt="logo Nearby">
      <h2 class="mt-2 text-sm">Temukan fasilitas kesehatan, pet hotel, pet shop di sekitar Jatinangor.</h2>
      <!-- button groups -->
      <div class="flex justify-around mt-5 font-medium text-xs">
        <button class="bg-[#EFEFEF] rounded-md py-1.5 px-4">Semua</button>
        <button class="bg-[#EFEFEF] rounded-md py-1.5 px-4">Klinik/RSH</button>
        <button class="bg-[#EFEFEF] rounded-md py-1.5 px-4">Shop</button>
        <button class="bg-[#EFEFEF] rounded-md py-1.5 px-4">Hotel</button>
      </div>
        <button class="bg-[#EFEFEF] border border-[#D9D9D9] rounded-md mt-3 py-2 px-4 w-full font-medium text-sm">Dekat Saya</button>
      <hr class="my-4 text-mist-200">
      <div class="flex items-start space-x-1.5">
        <img width="5%" src="/public/sort.svg" alt="sort icon">
        <p class="text-xs text-[#5A5A5A] italic">Mengurutkan yang terdekat dari kampus Unpad.</p>
      </div>
    </div>
  </section>

  <!-- section cards  -->
  <main class="mt-8 grid grid-cols-2 gap-y-4 gap-x-2 place-items-center">
    <div class="min-w-36 h-auto rounded-2xl shadow-sm bg-white py-3 px-3.5">
      <div class="flex gap-x-0.5">
        <img src="/public/location.svg" alt="location in card">
        <h4 class="font-medium text-xs text-[#929292]">Rancaekek</h4>
      </div>
      <h1 class="mt-1 text-xl font-bold leading-tight">Kaisar Petcare</h1>
      <div class="mt-3 flex gap-x-3">
        <img src="/public/klinik.svg"><img src="/public/hotel.svg" ><img src="/public/shop.svg">
      </div>
      <hr class="mt-5 my-2 text-[#EFEFEF]">
      <div class="flex gap-x-0.5">
        <div class="inline-flex gap-x-1">
          <img width="25%" src="/public/clock.svg" alt="">
          <h4 class="font-semibold text-xs">Buka </h4>
        </div>
        <div>
          <h4 class="text-xs">· Tutup 16.00</h4>
        </div>
      </div>
    </div>

    <div class="min-w-36 h-auto rounded-2xl shadow-sm bg-white py-3 px-3.5">
      <div class="flex gap-x-0.5">
        <img src="/public/location.svg" alt="location in card">
        <h4 class="font-medium text-xs text-[#929292]">Rancaekek</h4>
      </div>
      <h1 class="mt-1 text-xl font-bold leading-tight">Kaisar Petcare</h1>
      <div class="mt-3 flex gap-x-3">
        <img src="/public/klinik.svg"><img src="/public/hotel.svg" ><img src="/public/shop.svg">
      </div>
      <hr class="mt-5 my-2 text-[#EFEFEF]">
      <div class="flex gap-x-0.5">
        <div class="inline-flex gap-x-1">
          <img width="25%" src="/public/clock.svg" alt="">
          <h4 class="font-semibold text-xs">Buka </h4>
        </div>
        <div>
          <h4 class="text-xs">· Tutup 16.00</h4>
        </div>
      </div>
    </div>   

  </main>

  <!-- footer -->
   <footer class="pt-28 pb-10 text-center text-sm space-y-5">
    <p>Dibuat sebagai bentuk dukungan terhadap UMKM di sekitar Jatinangor dan rasa sayang kepada sesama pemilik hewan kesayangan.</p>
    <p>Dikembangkan oleh Peduli Hewan Jalanan Universitas Padjadjaran / Unpad Street Animal Friend</p>
    <div class="inline-flex space-x-2.5">
      <a href="http://github.com/unpadforstrays-dev" target="_blank" rel="noopener noreferrer">Github</a>
      <p>Terms of Use</p>
    </div>
    <img class="w-44 mx-auto" src="/public/research.webp" alt="logo UnpadSF Research">
   </footer>

</div>
</template>

<style scoped></style>
