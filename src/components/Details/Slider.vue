<template>
<div class="swiper mySwiper">
        <div class="swiper-wrapper">
            <div class="swiper-slide">
                <img src="./../../assets/about-3.jpg" alt="">
            </div>
            <div class="swiper-slide">
                <img src="./../../assets/about-4.jpg" alt="">
            </div>
            <div class="swiper-slide">
                <img src="./../../assets/about-5.jpg" alt="">
            </div>
        </div>

        <div class="container">
            <div class="swiper-button-next"></div>
            <div class="swiper-button-prev"></div>
        </div>
    </div>
</template>
<style scoped>
.swiper {
    height: 80vh;
    width: 100%;
}

.swiper-slide:hover img {
    transform: scale(1.05);
}

.swiper-slide img {
    transition: all .4s ease-in-out;
    width: 100%;
    height: 100%;
}

.swiper-button-next,
.swiper-button-prev {
    opacity: 0;
    visibility: hidden;
    transition: opacity 0.4s ease-in-out, visibility 0.4s ease-in-out;
    color: var(--secondary-color);
    background-color: rgb(from var(--primary-color) r g b/ 80%);
    height: 40px;
    width: 40px;
    border-radius: 50%;
}

.swiper-button-next::after,
.swiper-button-prev::after {
    font-size: 1.5rem !important;
}

.swiper:hover .swiper-button-next,
.swiper:hover .swiper-button-prev {
    opacity: 1;
    visibility: visible;
}
</style>