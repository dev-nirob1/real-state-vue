<script setup>
import Title from './Title.vue';

</script>

<template>
    <div class="bg-dark">
        <div class="container page-title py-1">
            <Title>
                <slot></slot>
            </Title>
            <p>
                <span class="material-symbols-outlined primary-color">
                    home
                </span> <a href="#">Home</a> <span class="material-symbols-outlined">
                    chevron_right
                </span> <span>
                    <slot></slot>
                </span>
            </p>
        </div>
    </div>
</template>
<style scoped>
.page-title p {
  display: flex;
  align-items: center;
  font-weight: 700;
}

.page-title a {
  transition: color .3s ease-in-out;
  color: var(--text-light-color);
}

.page-title a:hover {
  color: var(--primary-color);
}
</style>