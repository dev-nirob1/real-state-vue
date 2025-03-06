<script setup lang="ts">
import Statistics from '@/components/Home/Statistics.vue';
import About from '@/components/shared/About.vue';

</script>

<template>
  <About />
  <!-- about-us section ends -->

  <!-- stats section starts -->
  <div>
    <div class="large-2">
      <!-- image container  -->
      <div class="image-container">
        <img src="../assets/about-4.jpg" alt="">
      </div>
      <div class="bg-dark statistics text-light py-2">
        <Statistics></Statistics>
      </div>
    </div>
  </div>
  <!-- stats section ends -->


</template>

<style scoped>
.image-container {
  height: 100%;
}

.image-container img {
  height: 100%;
  width: 100%;
}

.statistics {
  height: 100%;
}

.statistics .stats-content {
  height: 100%;
}
</style>
