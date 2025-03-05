<template>
    <section id="gallery" class="container p-4">
        <div class="medium-2 large-3 gap-2">
            <div class="gallery-card">
                <div class="image-container">
                    <img class="image-responsive" src="./../assets/about-3.jpg" alt="">
                    <div class="gradient-overlay">
                        <button class="btn-search">
                            <span class="material-symbols-outlined">
                                search
                            </span>
                        </button>
                    </div>
                </div>
                <div class="card-content">
                    <h3>Football Tournament</h3>
                    <p class="text-light">Scion Team</p>
                </div>
            </div>
            <div class="gallery-card">
                <div class="image-container">
                    <img class="image-responsive" src="./../assets/about-5.jpg" alt="">
                    <div class="gradient-overlay">
                        <button class="btn-search">
                            <span class="material-symbols-outlined">
                                search
                            </span>
                        </button>
                    </div>
                </div>
                <div class="card-content">
                    <h3>Football Tournament</h3>
                    <p class="text-light">Scion Team</p>
                </div>
            </div>
            <div class="gallery-card">
                <div class="image-container">
                    <img class="image-responsive" src="./../assets/about-4.jpg" alt="">
                    <div class="gradient-overlay">
                        <button class="btn-search">
                            <span class="material-symbols-outlined">
                                search
                            </span>
                        </button>
                    </div>
                </div>
                <div class="card-content">
                    <h3>Picnic 2024</h3>
                    <p>Scion Office Staffs</p>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.image-container {
    position: relative;
    overflow: hidden;
    height: 300px;
}

.image-responsive {
    height: 100%;
    transition: transform 1s ease;
}

.gradient-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8));
    opacity: 0;
    transition: opacity 1s ease;
    display: flex;
    align-items: center;
    justify-content: center;
    color: var(--secondary-color);
}

.card-content {
    border: 1px solid var(--border-color);
    border-top: none;
    padding: 1rem;
}

.gallery-card:hover .image-responsive {
    transform: scale(1.1);
}

.gallery-card:hover .gradient-overlay {
    opacity: 1;
}

.btn-search {
    padding: 8px;
    border-radius: 50%;
    border: none;
    outline: none;
    color: var(--dark-color);
    background-color: var(--secondary-color);
}
</style>