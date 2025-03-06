<template>
    <div class="card">
        <img src="./../../assets/home-icon.png" alt="">
        <h4 class="heading-4 text-dark"><a href="#">Buy a home</a></h4>
        <p class="text-light my-1">
            over 1 million+ homes for sale available on the website, we can match you with a house you
            will
            want to call home.
        </p>
        <!-- link  -->
        <a class="flex align-center justify-center text-light my-1 link-btn" href="#">
            Find A Home
            <span class="material-symbols-outlined">
                arrow_right_alt
            </span>
        </a>
    </div>
</template>
<style scoped>
.card {
    background-color: var(--secondary-color);
    padding: 1rem;
    text-align: center;
    box-shadow: var(--services-card-shadow);
    transition: all .3s ease-in-out;
    border-bottom: 3px solid transparent;
}

.card:hover,
.card:focus,
.card:active {
    border-bottom: 3px solid var(--primary-color);
}

.card h3:hover {
    color: var(--primary-color);
    transition: color .3s ease-in-out;
}

.card:hover .link-btn {
    color: var(--primary-color);
    transition: color .3s ease-in-out;
}
</style>