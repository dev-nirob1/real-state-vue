<script setup lang="ts">
import SubTitle from '../shared/SubTitle.vue';
import Title from '../shared/Title.vue';
import ServicesCard from './ServicesCard.vue';

</script>

<template>
    <section class="bg-dark py-4">
        <div class="container">
            <!-- section header  -->
            <div class="text-center">
                <SubTitle>
                    Our Services
                </SubTitle>
                <Title>
                    Our Main Focus
                </Title>
            </div>
            <!-- card container  -->
            <div class="medium-2 large-3 gap-2">
                <!-- card  -->
                <ServicesCard />
                <ServicesCard />
                <ServicesCard />
            </div>
        </div>
    </section>
</template>
<style scoped></style>