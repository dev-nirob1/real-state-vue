<template>
    <div class="blog-card">
        <div class="relative card-image">
            <a class="image-responsive" href="#">
                <img class="image-responsive" src="./../../assets/menu-banner-1.jpg" alt="">
            </a>
        </div>
        <div class="p-1">
            <div class="all-2 mb-1">
                <a class="author-link flex items-center" href="#">
                    <span class="material-symbols-outlined primary-color">person</span>
                    <span class="text-light">by: Admin</span>
                </a>
                <div>
                    <a class="flex items-center" href="#">
                        <span class="material-symbols-outlined primary-color">
                            sell
                        </span>
                        <span class="text-light">Decorate</span>
                    </a>
                </div>
            </div>
            <h4 class="heading-4 text-dark mb-1">
                <a href="#">10 Brilliant Ways To Decorate Your Home</a>
            </h4>
            <hr>
            <div class="flex justify-between align-center my-1">
                <div class="flex items-center">
                    <span class="material-symbols-outlined primary-color">
                        calendar_month
                    </span> <span class="text-light">June 24, 2021</span>
                </div>
                <div>
                    <a class="primary-color" href="#">READ MORE</a>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.blog-card {
  overflow: hidden;
  font-family: var(--nunito-font);
  box-shadow: var(--blog-card-shadow);
}

.card-image {
  height: 280px;
  width: 100%;
  overflow: hidden;
}

.blog-card img {
  position: absolute;
  height: 100%;
  width: 100%;
  overflow: hidden;
  transition: all .5s ease-in-out;
}

.blog-card:hover img {
  transform: scale(1.1);
}

</style>