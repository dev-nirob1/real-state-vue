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