<script setup lang="ts">
import SubTitle from '../shared/SubTitle.vue';
import Title from '../shared/Title.vue';

</script>

<template>
    <section class="container py-4">
        <div class="text-center">
            <SubTitle>Apartment Sketch</SubTitle>
            <Title>Apartments Plan</Title>
        </div>
        <!-- categories or tab  -->
        <div class="para-md-size flex items-center flex-wrap justify-center gap-2 text-dark mb-3">
            <p>The Studio</p>
            <p>Deluxe Portion</p>
            <p>Penthouse</p>
            <p>Top Garden</p>
            <p>Double Height</p>
        </div>
        <!-- container  -->
        <div class="large-2 gap-3">
            <!-- text content  -->
            <div class="appartment-content">
                <h4 class="heading-4">Double Height</h4>
                <p class="mb-3">Enimad minim veniam quis nostrud exercitation ullamco laboris. Lorem
                    ipsum dolor sit
                    amet cons aetetur adipisicing elit sedo eiusmod tempor.Incididunt labore et dolore magna aliqua.
                    sed ayd minim veniam.</p>
                <p>Enimad minim veniam quis nostrud exercitation ullamco laboris. Lorem ipsum
                    dolor sit amet cons
                    aetetur adipisicing elit sedo eiusmod tempor.Incididunt labore et dolore magna aliqua. sed ayd
                    minim veniam.</p>
            </div>
            <!-- image container  -->
            <div class="image-responsive">
                <img class="image-responsive" src="./../../assets/sketch.png" alt="">
            </div>
        </div>
    </section>
</template>

<style scoped>
.appartment-content {
    padding: var(--appartment-content-padding);
    color: var(--secondary-color);
    background-color: var(--primary-color);
}
</style>