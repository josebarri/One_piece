<script setup>
import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'

// initialize components based on data attribute selectors
onMounted(() => {
  initFlowbite()
})
</script>
<template>
  <div class="">
    <figure
      class="relative max-w-full transition-all duration-300 cursor-pointer filter grayscale hover:grayscale-0"
    >
      <a href="#">
        <img
          class="rounded-none"
          src="https://images3.alphacoders.com/739/739912.jpg"
          alt="image description"
        />
      </a>
      <figcaption class="fixed px-56 text-2xl top-96 mt-56 text-white bottom-6">
        <p>¡No estamos preguntando donde está el tesoro escondido! ¡Ni siquiera estamos preguntando si existe un tesoro! Todos salieron al mar, ¡arriesgando su vida para buscarlo!</p>
      </figcaption>
    </figure>
  </div>
  <!-- <div class="grid gap-4">
    <div>
      <a
        href="#"
        class="flex flex-col items-center bg-white border border-gray-200 rounded-lg shadow md:flex-row md:max-w-xl hover:bg-gray-100 dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700"
      >
        <img
          class="object-cover w-full rounded-t-lg h-96 md:h-auto md:w-48 md:rounded-none md:rounded-l-lg"
          src="https://mangaplus.shueisha.co.jp/drm/title/200016/title_thumbnail_portrait_list/14332.jpg?key=0c019b899952b1ba2468d442495e1e83&duration=86400"
          alt=""
        />
        <div class="flex flex-col justify-between p-4 leading-normal">
          <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
            Noteworthy technology acquisitions 2021
          </h5>
          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
            Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse
            chronological order.
          </p>
        </div>
      </a>
    </div>
  </div> -->
</template>
