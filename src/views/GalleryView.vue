<script setup lang="ts">
import GalleryCard from '@/components/Gallery/GalleryCard.vue';
import PageTitle from '@/components/shared/PageTitle.vue';

</script>

<template>
    <PageTitle>
        Gallery
    </PageTitle>
    <section id="gallery" class="container py-4">
        <div class="medium-2 large-3 gap-2">
            <GalleryCard/>
            <GalleryCard/>
            <GalleryCard/>
        </div>
    </section>
</template>
