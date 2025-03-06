<template>
    <div class="properties-card">
        <div class="relative image-responsive">
            <div class="relative card-image">
                <a class="image-responsive" href="#">
                    <img class="image-responsive title-image" src="./../../assets/menu-banner-1.jpg" alt="">
                </a>
            </div>
            <div>
                <span class="badge rent">FOR RENT</span>
            </div>
        </div>
        <div class="text-light p-1">
            <p class="primary-color"> <span class="para-md-size font-bold">$34,900</span>/Month</p>
            <h4 class="heading-4 text-dark my-1"><a href="#">Modern Apartments</a></h4>
            <p class="line-height-1">Beautiful Huge 1 Family House In Heart Of <br>
                Westbury. Newly Renovated With New Wood</p>
            <div class="all-3 align-center gap-1 icon-container">
                <small class="card-icon">
                    <small class="flex items-center">3 <span class="material-symbols-outlined">
                            king_bed
                        </span> </small>
                    <span>Bedrooms</span>
                </small>
                <small class="card-icon">
                    <small class="flex items-center">2 <span class="material-symbols-outlined">
                            <span class="material-symbols-outlined">
                                bathtub
                            </span>
                        </span></small>
                    <span>Bathrooms</span>
                </small>
                <small class="card-icon">
                    <small class="flex items-center">335 <span class="material-symbols-outlined">
                            king_bed
                        </span></small>
                    <span>square Ft</span>
                </small>
            </div>
        </div>
    </div>
</template>

<style scoped>
.properties-card {
    box-shadow: var(--properties-card-shadow);
    overflow: hidden;
    transition: all .3s ease-in-out;
}

.properties-card img {
    overflow: hidden;
    transition: all .5s ease-in-out;
}

.properties-card:hover .title-image {
    width: 100%;
    height: auto;
    transform: scale(1.1);
}

.properties-card a:hover {
    color: var(--primary-color);
}

.icon-container {
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
}

.properties-card .sale {
    background-color: #54ecad;
    color: var(--secondary-color);
}

.properties-card .rent {
    color: var(--secondary-color);
    background-color: var(--primary-color);
}
</style>