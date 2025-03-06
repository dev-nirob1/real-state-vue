<template>
    <div class="properties-card">
                <div class="relative title-image">
                    <img class="image-responsive" src="./../../assets/about-3.jpg" alt="">
                </div>
                <div class="text-light p-1">
                    <span class="primary-color">ON GOING</span>
                    <h4 class="heading-4 my-1 text-dark"><a href="#">Modern Apartments</a></h4>
                    <a class="flex mb-1" href="#">
                        <span class="material-symbols-outlined location-icon">
                            location_on
                        </span>
                        <small>Brooklyn, New York, United States</small>
                    </a>
                    <div>
                        <p><strong>3.8 </strong>Katha, Height: <strong>G 7</strong></p>
                    </div>
                </div>
            </div>
</template>

<style scoped>
.properties-card {
    box-shadow: var(--properties-card-shadow);
    overflow: hidden;
    transition: all .5s ease-in-out;
}
.properties-card .title-image{
    height: 300px;
    width: 100%;
    overflow: hidden;
}

.properties-card img {
    height: 100%;
    width: 100%;
    transition: all .5s ease-in-out;
}
.properties-card a{
    transition: all .3s ease-in-out;
}

.properties-card:hover img {
    transform: scale(1.1);
}

.properties-card a:hover {
    color: var(--primary-color);
}

/* .icon-container {
    color: var(--light-color);
    margin: 1rem 0;
}

.icon-container .card-icon:not(:last-child) {
    border-right: 1px solid var(--border-color);
    padding: 6px;
}

.properties-card .badge {
    position: absolute;
    top: 1rem;
    right: 1rem;
    font-size: 14px;
    padding: 4px 8px;
} */

</style>