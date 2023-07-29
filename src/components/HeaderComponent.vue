<script setup>
import { Button } from 'flowbite-vue';
</script>
<template>
  <div class="flex flex-row mt-5">
    <div class="basis-1/2">
      <h1 class="selamatdatang pt-16">Web PortoFolio Saya</h1>
      <p class="font-semibold"></p>
      <a href="#bio"><Button color="default" class="mt-4">Lihat</Button></a>
    </div>
    <div class="basis-1/2">
      <img src="/img/aku.jpg" width="350" alt="" class="ml-8 hover:scale-125 transition-all hover:hue-rotate rounded-full" />
    </div>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap');

.selamatdatang {
  font-family: 'Montserrat', sans-serif;
  font-size: 70px;
  font-weight: bold;
}
</style>