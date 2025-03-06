<script setup lang="ts">
import SubTitle from '../shared/SubTitle.vue';
import Title from '../shared/Title.vue';
import PropertiesCard from './PropertiesCard.vue';

</script>

<template>
    <section class="container py-4">
        <div class="text-center">

            <SubTitle>Properties</SubTitle>
            <Title>Featured Listings</Title>
        </div>
        <!-- card container  -->
        <div class="medium-2 large-3 gap-2">
            <!-- card  -->
            <PropertiesCard/>
            <PropertiesCard/>
            <PropertiesCard/>
        </div>
    </section>
</template>
<style scoped>

</style>