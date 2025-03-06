<template>
    <div class="all-3 gap-1">
        <a href="#">
            <img class="product-image" src="./../../../assets/about-5.jpg" alt="">
        </a>
        <div class="span-2">
            <div class="stars">
                <span class="material-symbols-outlined">
                    star
                </span>
                <span class="material-symbols-outlined">
                    star
                </span>
                <span class="material-symbols-outlined">
                    star
                </span>
                <span class="material-symbols-outlined">
                    star
                </span>
                <span class="material-symbols-outlined">
                    star
                </span>
            </div>
            <div>
                <a class="link" href="#">
                    <h5>Luxury House In Greenville</h5>
                </a>
                <div>
                    <span class="price">$30,000.00</span> <del class="prev-price">$35,000.00</del>
                </div>

            </div>
        </div>
    </div>
</template>
<style scoped>
.product-image {
    height: 70px;
    width: 100%;
}

.stars {
    display: flex;
    align-items: center;
}

.stars span {
    font-size: 1rem;
    color: rgb(253, 161, 14);
}

.price {
    color: var(--primary-color);
    font-weight: 600;
}

.prev-price {
    color: var(--primary-color);
    text-decoration: line-through;
}</style>