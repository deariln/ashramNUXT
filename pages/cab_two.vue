<template>
    <div class="box">
        <Swiper :navigation="true" :modules="modules" class="mySwiper">
            <SwiperSlide><img src="/public/photo/comfort-1.jpg" alt="#"></SwiperSlide>
            <SwiperSlide><img src="/public/photo/comfort-2.jpg" alt="#"></SwiperSlide>
            <SwiperSlide><img src="/public/photo/comfort-3.jpg" alt="#"></SwiperSlide>
            <SwiperSlide><img src="/public/photo/comfort-4.jpg" alt="#"></SwiperSlide>
            <SwiperSlide><img src="/public/photo/comfort-5.jpg" alt="#"></SwiperSlide>
            <SwiperSlide><img src="/public/photo/comfort-6.jpg" alt="#"></SwiperSlide>
        </Swiper>
        <div class="div-ul">
            <p class="h2">
        Кабинет Комфорт
            </p>
            <ul class="ul-box">
                <li>Кушетка у которой поднимается спинка</li>
                <li>Гримерный стол</li>
                <li>Расходные материалы</li>
                <li>Аренда хранения материалов</li>
                <li>Оборудование для фото и видео</li>
            </ul>
            <NuxtLink to="/" class="box-button">
                На главную
                </NuxtLink>
        </div>
    </div>
</template>

<script setup lang="ts">
definePageMeta({
    layout: 'cab'
})
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue';
// import required modules
import { Navigation } from 'swiper/modules';
// Import Swiper styles
import 'swiper/css';
import 'swiper/css/navigation';
const modules = [Navigation]

</script>

<style scoped>
.mySwiper {
    height: 700px;
    width: 700px;
    margin: 0;
}

.box {
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 30px;
    gap: 50px;
}

.box-button {
    color: rgb(70, 70, 70);
    background: transparent;
    border-radius: 20px;
    padding: 5px;
    font-size: 18px;
    width: 200px;
    margin: 10px;
    border: 1px solid black;
    text-decoration: none;
    text-align: center;
    margin-top: 20px;
    margin-left: 50px;
}

.ul-box {
    font-size: 20px;
    list-style-type: disc;
    margin-left: 50px;
}
.h2 {
    font-size: 30px;
    text-align: center;
    padding: 20px;
    background-color: rgb(255, 255, 255);
    margin-left: 20px;
}

.div-ul {
    display: flex;
    flex-direction: column;
}
</style>