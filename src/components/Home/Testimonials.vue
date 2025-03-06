<script setup lang="ts">
import SubTitle from '../shared/SubTitle.vue';
import Title from '../shared/Title.vue';
import TestimonialsCard from './TestimonialsCard.vue';

</script>

<template>
    <section class="bg-dark py-4">
            <div id="testimonials" class="container">
                <div class="text-center">
                    <SubTitle>Our Testimonial</SubTitle>
                    <Title>Clients Feedback</Title>
                </div>
                <!-- testimonials container  -->
                <div class="medium-2 large-3 gap-2">
                    <!-- cards  -->
                    <TestimonialsCard/>
                    <TestimonialsCard/>
                    <TestimonialsCard/>
                </div>
            </div>
        </section>
</template>