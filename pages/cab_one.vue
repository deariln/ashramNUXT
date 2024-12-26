<template>
    <h1 class="h1">
        Гримерный стол
    </h1>
    <div class="box">
        <Swiper :navigation="true" :modules="modules" class="mySwiper">
            <SwiperSlide><img src="/public/photo/cab-one1.jpeg" alt="#"></SwiperSlide>
            <SwiperSlide><img src="/public/photo/cab-one2.jpeg" alt="#"></SwiperSlide>
            <SwiperSlide><img src="/public/photo/cab-one3.jpeg" alt="#"></SwiperSlide>
            <SwiperSlide><img src="/public/photo/cab-one4.jpeg" alt="#"></SwiperSlide>
            <SwiperSlide><img src="/public/photo/cab-one5.jpeg" alt="#"></SwiperSlide>
            <SwiperSlide><img src="/public/photo/cab-one6.jpeg" alt="#"></SwiperSlide>
        </Swiper>
        <div class="div-ul">
            <ul class="ul-box">
                <li>2 гримерных места</li>
                <li>Расходные материалы входят в стоимость</li>
                <li>В гримерке стоит кулер</li>
                <li>Чай, кофе, вода, сладости</li>
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
.h1 {
    font-size: 20px;
    text-align: center;
    padding: 20px;
    background-color: gainsboro;
    color: black;
}

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
</style>