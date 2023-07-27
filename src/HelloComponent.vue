<template>
     <center><b class="p-2"
            style="font-size: 30px; text-align: center; color: black; font-family: 'sans-serif', Calibri, 'Trebuchet MS', sans-serif;">Vidio</b>
    </center>
    <center> <div style="width: 10%; background: grey; height: 2px;"></div></center>
  <div class="grid grid-cols-3 gap-4">
    <div class=" pl-10 a">
      <the-card>
        <iframe src="https://www.youtube.com/embed/SGFjQqS_kpI" title="YouTube video player"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen></iframe>
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Membangun Generasi Yang Kokoh Dicintai Allah</h5>
        <p class="font-normal text-gray-700 dark:text-gray-400">Ustadz. Abdul Somad</p>
      </the-card>
    </div>
    <div class="px-5 b">
      <the-card>
        <iframe src="https://www.youtube.com/embed/TvmKT5gJCRE" title="YouTube video player"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen></iframe>
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Amalan Terakhir Seorang Muslim Di Dunia</h5>
        <p class="font-normal text-gray-700 dark:text-gray-400">Ustadz Adi Hidayat</p>
      </the-card>
    </div>
    <div class="pr-10 c">
      <the-card>
        <iframe src="https://www.youtube.com/embed/sy-HbOc1RkA" title="YouTube video player"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen></iframe>
          <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">HIDUPMU AKAN MENJADI LEBIH BAIK</h5>
          <p class="font-normal text-gray-700 dark:text-gray-400"> Ustadz Hanan Attaki </p>
      </the-card>
    </div>
    <div class=" pl-10 a">
      <the-card>
        <iframe src="https://www.youtube.com/embed/HVbzfvGx8JA" title="YouTube video player"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen></iframe>
          <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">KUNCI MENCAPAI HATI YANG TENANG</h5>
        <p class="font-normal text-gray-700 dark:text-gray-400">Ustadz. Abdul Somad</p>
      </the-card>
    </div>
    <div class="px-5 b">
      <the-card>
        <iframe src="https://www.youtube.com/embed/izYUMrsvVDQ" title="YouTube video player"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen></iframe>
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Hadiah Allah Ketika Mengalami</h5>
        <p class="font-normal text-gray-700 dark:text-gray-400">Ustadz Adi Hidayat</p>
      </the-card>
    </div>
    <div class="pr-10 c">
      <the-card>
        <iframe src="https://www.youtube.com/embed/1erMtB_B1qM" title="YouTube video player"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen></iframe>
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Jangan Khawatir Dengan Masadepanmu</h5>
        <p class="font-normal text-gray-700 dark:text-gray-400"> Ustadz Hanan Attaki </p>
      </the-card>
    </div>
  </div>
</template>

<script setup>
import { TheCard } from 'flowbite-vue'
</script>