<template>
    <a class="aminities-card p-1" href="#">
        <span class="icon">
            <i class="material-icons">house</i>
        </span>
        <h4 class="heading-4 my-2">Smart Homes</h4>
        <div class="arrow-btn">
            <span class="material-symbols-outlined">
                arrow_right_alt
            </span>
        </div>
    </a>
</template>
<style scoped>
.aminities-card {
    position: relative;
    text-align: center;
    border-radius: 8px;
    box-shadow: var(--aminities-card-shadow);
    margin-bottom: 1.5rem;
    transition: all .4s ease-in-out;
}

.aminities-card:hover {
    background-color: var(--primary-color);
    color: var(--secondary-color);
}

.aminities-card:hover .arrow-btn span {
    color: var(--primary-color);
    transition: all .3s ease-in-out;
}

.aminities-card .icon {
    background-color: var(--bg-light);
    color: var(--primary-color);
    height: 100px;
    width: 100px;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 100%;
}

.icon i {
    font-size: 45px;
}

.arrow-btn {
    position: absolute;
    bottom: -5px;
    height: 50px;
    width: 50px;
    left: 50%;
    transform: translate(-50%, 50%);
    color: var(--text-light-color);
    background-color: var(--secondary-color);
    box-shadow: var(--arrow-btn-shadow);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
}

.arrow-btn span {
    font-size: 30px;
}
</style>