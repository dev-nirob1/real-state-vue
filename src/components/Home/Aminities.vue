<script setup lang="ts">
import SubTitle from '../shared/SubTitle.vue';
import Title from '../shared/Title.vue';
import AminitiesCard from './AminitiesCard.vue';

</script>

<template>
   <section class="container py-4">
            <div class="text-center">
                <SubTitle>Our Aminities</SubTitle>
                <Title>Building Aminities</Title>
            </div>
            <!-- container  -->
            <div class="medium-2 large-3 larger-4 gap-2">
                <!-- cards  -->
                <AminitiesCard/>
                <AminitiesCard/>
                <AminitiesCard/>
                <AminitiesCard/>
                <AminitiesCard/>
                <AminitiesCard/>
                <AminitiesCard/>
                <AminitiesCard/>
            </div>
        </section>
</template>