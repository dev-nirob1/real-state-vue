<template>
  <!-- page title  -->
  <div class="bg-dark">
    <div class="container page-title">
      <h3 class="title">About Us</h3>
      <p><span class="material-symbols-outlined primary-color">
          home
        </span> <a href="#">Home</a> <span class="material-symbols-outlined">
          chevron_right
        </span> <span>About Us</span></p>
    </div>
  </div>
  <!-- page title ends -->
  <!-- about-us section starts -->
  <section class="container text-light p-4">
    <div class="large-2 align-center gap-2">
      <!-- image div  -->
      <div class="image-responsive relative">
        <img class="image-responsive" src="../assets/about-us-1.png" alt="image">
        <div class="video-image">
          <div class="image-responsive relative">
            <img class="image-responsive" src="../assets/about-us-2.png" alt="image">
            <!-- play btn  -->
            <button class="btn-circle btn-center-align">
              <span class="material-symbols-outlined">
                play_arrow
              </span>
            </button>
          </div>
        </div>
      </div>
      <!-- wrapper div for content  -->
      <div>
        <!-- section header div starts -->
        <div>
          <h5 class="sub-title">
            About Us
          </h5>
          <h3 class="title text-dark">
            The Leading Real Estate Rental Marketplace.
          </h3>
        </div>
        <!-- section header div ends -->
        <p class="text-light mb-1">Over 39,000 people work for us in more than 70 countries
          all over the
          This breadth of global
          coverage, combined with specialist services
        </p>
        <!-- icon + title container  -->
        <div class="all-2 align-center">
          <div class="flex align-center mb-1">
            <span class="material-symbols-outlined about-icons">
              home
            </span>
            <p>Smart Home Design</p>
          </div>
          <div class="flex align-center">
            <span class="material-symbols-outlined about-icons">
              landscape_2
            </span>
            <p>Beautiful Scene Around</p>
          </div>
          <div class="flex align-center mb-1">
            <span class="material-symbols-outlined about-icons">
              heart_plus
            </span>
            <p>Exceptional Lifestyle</p>
          </div>
          <div class="flex align-center">
            <span class="material-symbols-outlined about-icons">
              encrypted_add
            </span>
            <p>Complete 24/7 Security</p>
          </div>
        </div>
        <!-- icon + title container ends  -->
        <p class="about-quote ">
          "Enimad minim veniam quis nostrud exercitation
          llamco laboris. Lorem ipsum dolor sit amet"
        </p>
        <button class="btn btn-primary">OUR SERVICES</button>
      </div>
    </div>
  </section>
  <!-- about-us section ends -->

  <!-- stats section starts -->
  <div>
    <div class="large-2">
      <!-- image container  -->
      <div class="image-container">
        <img src="../assets/about-4.jpg" alt="">
      </div>

      <div class="bg-dark statistics text-light py-2">
        <div class="small-2 larger-4 gap-1 stats-content">
          <!-- individual stats component  -->
          <div class="flex-col justify-center align-center text-center">
            <span class="material-symbols-outlined statistics-icons">
              crop_square
            </span>
            <h3 class="title text-dark">560+</h3>
            <p class="font-bold">Total Area Sq</p>
          </div>
          <div class="flex-col justify-center align-center text-center">
            <span class="material-symbols-outlined statistics-icons">
              apartment
            </span>
            <h3 class="title text-dark">197K+</h3>
            <p class=" font-bold">Apartments Sold</p>
          </div>
          <div class="flex-col justify-center align-center text-center">
            <span class="material-symbols-outlined statistics-icons">
              precision_manufacturing
            </span>
            <h3 class="title text-dark">268+</h3>
            <p class=" font-bold">Total Constructions</p>
          </div>
          <div class="flex-col justify-center align-center text-center">
            <span class="material-symbols-outlined statistics-icons">
              chair
            </span>
            <h3 class="title text-dark">340+</h3>
            <p class=" font-bold">Apartio Rooms</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- stats section ends -->


</template>

<style>
.image-container {
  height: 100%;
}

.image-container img {
  height: 100%;
  width: 100%;
}

.statistics {
  height: 100%;
}

.stats-content {
  height: 100%;
  align-items: center;
}
</style>
