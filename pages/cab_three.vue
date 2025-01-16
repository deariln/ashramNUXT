<template>
    <h3 class="h3">
        Кабинет Стандарт
    </h3>
    <div class="box">
        <Swiper :navigation="true" :modules="modules" class="mySwiper">
            <SwiperSlide><img src="/public/photo/standart-1.jpg" alt="#"></SwiperSlide>
            <SwiperSlide><img src="/public/photo/standart-2.jpg" alt="#"></SwiperSlide>
            <SwiperSlide><img src="/public/photo/standart-3.jpg" alt="#"></SwiperSlide>
            <SwiperSlide><img src="/public/photo/standart-4.jpg" alt="#"></SwiperSlide>
            <SwiperSlide><img src="/public/photo/cab-one5.jpeg" alt="#"></SwiperSlide>
            <SwiperSlide><img src="/public/photo/cab-one6.jpeg" alt="#"></SwiperSlide>
        </Swiper>
        <div class="div-ul">
            <ul class="ul-box">
                <li>Гримерный стол</li>
                <li>Кушетка с вырезом для лица</li>
                <li>Мягкий ортопедический массаж</li>
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
}

.ul-box {
    font-size: 20px;
    list-style-type: disc;
}
.h3 {
    font-size: 30px;
    text-align: center;
    padding: 20px;
    background-color: rgb(255, 255, 255);
}

.div-ul {
    display: flex;
    flex-direction: column;
}
</style>