<script setup>
import { RouterView } from 'vue-router'
import Footer from './components/shared/Footer.vue';
import Header from './components/shared/Header.vue';
</script>

<template>
  <Header></Header>
  <RouterView></RouterView>
  <Footer ></Footer>
</template>

