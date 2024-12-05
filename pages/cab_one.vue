<template>
    <h1 class="h1">
        Гримерный стол
    </h1>
    <Swiper :navigation="true" :modules="modules" class="mySwiper">
    <SwiperSlide>Slide 1</SwiperSlide>
    <SwiperSlide>Slide 2</SwiperSlide>
    <SwiperSlide>Slide 3</SwiperSlide>
    <SwiperSlide>Slide 4</SwiperSlide>
    <SwiperSlide>Slide 5</SwiperSlide>
    <SwiperSlide>Slide 6</SwiperSlide>
    <SwiperSlide>Slide 7</SwiperSlide>
    <SwiperSlide>Slide 8</SwiperSlide>
    <SwiperSlide>Slide 9</SwiperSlide>
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
    height: 300px;
}
</style>