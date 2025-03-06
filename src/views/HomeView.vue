<script setup>
import About from '@/components/shared/About.vue';
import AboutUs from '@/components/Home/AboutUs.vue';
import Aminities from '@/components/Home/Aminities.vue';
import ApartmentSketch from '@/components/Home/ApartmentSketch.vue';
import Banner from '@/components/Home/Banner.vue';
import Blogs from '@/components/Home/Blogs.vue';
import Parallax from '@/components/Home/Parallax.vue';
import Properties from '@/components/Home/Properties.vue';
import Services from '@/components/Home/Services.vue';
import Statistics from '@/components/Home/Statistics.vue';
import Testimonials from '@/components/Home/Testimonials.vue';

</script>

<template>
    <!-- main content -->
    <main>
        <Banner />
        <About />
        <Statistics />
        <AboutUs />
        <Services />
        <Properties />
        <ApartmentSketch />
        <Parallax />
        <Aminities />
        <Testimonials />
        <Blogs/>
    </main>
</template>
