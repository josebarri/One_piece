<template>
  <section>
    <!-- <fwb-card>
            <div class="my-3">
                <img class="image" src="https://picfiles.alphacoders.com/645/645551.jpeg" alt="">
            </div>
            <img class="image1" src="/src/assets/image/logo.png" alt="">
            
        </fwb-card> -->
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4 p-9 m-10">
      <div
        class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
      >
        <a href="#">
          <img class="image4" src="/src/assets/image/sanji.png" alt="" />
        </a>
      </div>

      <div
        class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
      >
        <a href="#">
          <img class="image2" src="/src/assets/image/luffy.png" alt="" />
        </a>
      </div>

      <div
        class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
      >
        <a href="#">
          <img class="image1" src="/src/assets/image/zoro.png" alt="" />
        </a>
      </div>
    </div>
  </section>

  <section class="body">
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4 p-9 m-10"> 
        <div class="card">
            
            <div class="image-box">
             
                <img src="/src/assets/image/mustang.jpg" alt="">
            </div>
              
            <div class="content">
                <h2>Ford Mustang 1969</h2>
                <p>descripcion...</p>

            </div>

        </div>

        <div class="card">
            
            <div class="image-box">
             
                <img src="/src/assets/image/mustang.jpg" alt="">
            </div>
              
            <div class="content">
                <h2>Ford Mustang 1969</h2>
                <p>descripcion...</p>

            </div>

        </div>

        <div class="card">
            
            <div class="image-box">
             
                <img src="/src/assets/image/mustang.jpg" alt="">
            </div>
              
            <div class="content">
                <h2>Ford Mustang 1969</h2>
                <p>descripcion...</p>

            </div>

        </div>

       
    </div>
  </section>
</template>
<script setup>
import { FwbCard } from 'flowbite-vue'
import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'

onMounted(() => {
  initFlowbite()
})
</script>
<style>
.image2 {
  filter: drop-shadow(10px 7px 20px rgb(248, 2, 2));
}
.image4 {
  filter: drop-shadow(10px 7px 20px rgb(248, 191, 2));
}
.image5 {
  box-shadow: 10px 7px 20px rgb(42, 168, 3);
}
.image1 {
  filter: drop-shadow(10px 7px 20px rgba(42, 168, 3));
}


.card {
  width: 400px;
  aspect-ratio: 1 / 0.7;
  border-radius: 8px;
  position: relative;
  cursor: pointer;
}
.card .image-box {
  width: 100%;
  height: 100%;
  border-radius: inherit;
}
.card .image-box img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: 50% 90%;
  border-radius: inherit;
  transition: 0.5s ease-in-out;
}

.card::after {
  content: "";
  position: absolute;
  inset: 0;
  border: 2px solid white;
  border-radius: inherit;
  opacity: 0;
  transition: 0.4s ease-in-out;
}

.card:hover img {
  filter: grayscale(1) brightness(0.4);
}
.card:hover::after {
  opacity: 1;
  inset: 20px;
}

.content {
  width: 80%;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
}

.content h2,
.content p {
  opacity: 0;
  transition: 0.4s 0.2s ease;
}
.content h2 {
  margin-bottom: 12px;
  scale: 0.7;
  color: #d1d1d1;
}
.content p {
  font-size: 14px;
  line-height: 1.5;
  color: #d1d1d1;
  transform: translateY(50%);
}
.card:hover .content h2 {
  scale: 1;
  opacity: 1;
}
.card:hover .content P {
  opacity: 1;
  transform: translateY(0);
}

</style>
