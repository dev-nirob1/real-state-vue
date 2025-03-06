<script setup lang="ts">
import SubTitle from '../shared/SubTitle.vue';
import Title from '../shared/Title.vue';
import BlogsCard from './BlogsCard.vue';

</script>

<template>
    <section class="container py-4">
        <!-- section header  -->
        <div class="text-center">
            <SubTitle>News & Blogs</SubTitle>
            <Title>Leatest News Feeds</Title>
        </div>
        <!-- card container  -->
        <div class="medium-2 large-3 gap-2">
            <!-- individual card  -->
            <BlogsCard />
            <BlogsCard />
            <BlogsCard />
        </div>
    </section>
</template>