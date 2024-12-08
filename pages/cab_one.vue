<template>
    <h1 class="h1">
        Гримерный стол
    </h1>
    <Swiper :navigation="true" :modules="modules" class="mySwiper">
    <SwiperSlide><img src="/public/photo/cab-one1.jpeg" alt="#"></SwiperSlide>
    <SwiperSlide><img src="/public/photo/cab-one2.jpeg" alt="#"></SwiperSlide>
    <SwiperSlide><img src="/public/photo/cab-one3.jpeg" alt="#"></SwiperSlide>
    <SwiperSlide><img src="/public/photo/cab-one4.jpeg" alt="#"></SwiperSlide>
    <SwiperSlide><img src="/public/photo/cab-one5.jpeg" alt="#"></SwiperSlide>
    <SwiperSlide><img src="/public/photo/cab-one6.jpeg" alt="#"></SwiperSlide>
  </Swiper>
</template>

<script setup lang="ts">
definePageMeta({
    layout:'cab'
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
}
.mySwiper {
    height: 700px;
    width: 700px;
}
</style>