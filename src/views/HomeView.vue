<script setup>
import About from '@/components/Home/About.vue';
import AboutUs from '@/components/Home/AboutUs.vue';
import Banner from '@/components/Home/Banner.vue';
import Statistics from '@/components/Home/Statistics.vue';
import Title from '@/components/Title.vue';

</script>

<template>
    <!-- main content -->
    <main>
        <Banner/>
        <About/>
        <Statistics/>
        <AboutUs/>
        <!-- -------------statistics section starts here ------------------ -->
       
        <!-- ------------------------statistics section ends here------------------  -->

        <!-- -------------------about-us-2 section starts here ----------------- -->
        
        <!-- ----------------about-us-2 section ends here  --------------------------->

        <!-- ----------------services section starts here----------------------  -->
        <section class="bg-dark py-4">
            <div id="services" class="container">
                <!-- section header  -->
                <div class="text-center">
                    <h5 class="sub-title">Our Services </h5>
                        <h3 class="title">Our Main Focus </h3>
                </div>
                <!-- card container  -->
                <div class="medium-2 large-3 gap-2">
                    <!-- card  -->
                    <div class="card">
                        <img src="./../assets/home-icon.png" alt="">
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
                    <div class="card">
                        <img src="./../assets/home-icon.png" alt="">
                        <h4 class="heading-4 text-dark"><a href="#">Buy a home</a></h4>
                        <p class="text-light my-1">
                            over 1 million+ homes for sale available on the website, we can match you with a house you
                            will
                            want to call home.
                        </p>
                        <a class="flex align-center justify-center text-light my-1 link-btn" href="#">
                            Find A Home
                            <span class="material-symbols-outlined">
                                arrow_right_alt
                            </span>
                        </a>
                    </div>
                    <div class="card">
                        <img src="./../assets/home-icon.png" alt="">
                        <h4 class="heading-4 text-dark"><a href="#">Buy a home</a></h4>
                        <p class="text-light my-1">
                            over 1 million+ homes for sale available on the website, we can match you with a house you
                            will
                            want to call home.
                        </p>
                        <a class="flex align-center justify-center text-light my-1 link-btn" href="#">
                            Find A Home

                            <span class="material-symbols-outlined">
                                arrow_right_alt
                            </span>
                        </a>
                    </div>
                </div>
            </div>
        </section>
        <!-- ----------------------services section ends here--------------------  -->

        <!------------------- properties section starts here--------------------  -->
        <section class="container py-4">
            <div class="text-center">
                <h5 class="sub-title">Properties</h5>
                <h3 class="title">Featured Listings</h3>
            </div>
            <!-- card container  -->
            <div class="medium-2 large-3 gap-2">
                <!-- card  -->
                <div class="properties-card">
                    <div class="relative image-responsive">
                        <div class="relative card-image">
                            <a class="image-responsive" href="#">
                                <img class="image-responsive title-image" src="./../assets/menu-banner-1.jpg" alt="">
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
                    <hr>
                    <div class="product-info-bottom">
                        <div class="flex align-center gap-1">
                            <img class="profile" src="./../assets/author.jpg" alt="profile">
                            <div>
                                <h5 class="text-dark">Adam Josheph</h5>
                                <small class="text-light">Selling Agent</small>
                            </div>
                        </div>
                        <div class="flex gap-1">
                            <span class="material-symbols-outlined">
                                open_in_full
                            </span>
                            <span class="material-symbols-outlined">
                                favorite
                            </span>
                            <span class="material-symbols-outlined">
                                add
                            </span>
                        </div>
                    </div>
                </div>
                <div class="properties-card">
                    <div class="relative image-responsive">
                        <div class="relative card-image">
                            <a class="image-responsive" href="#">
                                <img class="image-responsive title-image" src="./../assets/menu-banner-1.jpg" alt="">
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
                    <hr>
                    <div class="product-info-bottom">
                        <div class="flex align-center gap-1">
                            <img class="profile" src="./../assets/author.jpg" alt="profile">
                            <div>
                                <h5 class="text-dark">Adam Josheph</h5>
                                <small class="text-light">Selling Agent</small>
                            </div>
                        </div>
                        <div class="flex gap-1">
                            <span class="material-symbols-outlined">
                                open_in_full
                            </span>
                            <span class="material-symbols-outlined">
                                favorite
                            </span>
                            <span class="material-symbols-outlined">
                                add
                            </span>
                        </div>
                    </div>
                </div>
                <div class="properties-card">
                    <div class="relative image-responsive">
                        <div class="relative card-image">
                            <a class="image-responsive" href="#">
                                <img class="image-responsive title-image" src="./../assets/menu-banner-1.jpg" alt="">
                            </a>
                        </div>
                        <div>
                            <span class="badge rent">FOR RENT</span>
                        </div>
                        <!-- <div class="location-container flex justify-between">
                            <p><a class="flex" href="#">
                                    <span class="material-symbols-outlined">
                                        location_on
                                    </span> belmont gardens, chicago
                                </a></p>
                            <div class="product-image-gallery">
                                <a href="#">
                                    <span class="material-symbols-outlined">
                                        photo_camera
                                    </span>
                                </a>
                                <a href="#">
                                    <span class="material-symbols-outlined">
                                        photo_camera
                                    </span>
                                </a>
                            </div>
                        </div> -->
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
                    <hr>
                    <div class="product-info-bottom">
                        <div class="flex align-center gap-1">
                            <img class="profile" src="./../assets/author.jpg" alt="profile">
                            <div>
                                <h5 class="text-dark">Adam Josheph</h5>
                                <small class="text-light">Selling Agent</small>
                            </div>
                        </div>
                        <div class="flex gap-1">
                            <span class="material-symbols-outlined">
                                open_in_full
                            </span>
                            <span class="material-symbols-outlined">
                                favorite
                            </span>
                            <span class="material-symbols-outlined">
                                add
                            </span>
                        </div>
                    </div>
                </div>

            </div>
        </section>
        <!-- -------------------------properties section ends here-------------------------  -->

        <!-- --------------------------apartment section starts here -------------------- -->
        <section class="container py-4">
            <div class="text-center">
                <h5 class="sub-title">Apartment Sketch</H5>
                    <h3 class="title">Apartments Plan</h3>
            </div>
            <!-- categories or tab  -->
            <div class="para-md-size flex items-center flex-wrap justify-center gap-2 text-dark mb-3">
                <p>The Studio</p>
                <p>Deluxe Portion</p>
                <p>Penthouse</p>
                <p>Top Garden</p>
                <p>Double Height</p>
            </div>
            <!-- container  -->
            <div class="large-2 gap-3">
                <!-- text content  -->
                <div class="appartment-content">
                    <h4 class="heading-4">Double Height</h4>
                    <p class="mb-3">Enimad minim veniam quis nostrud exercitation ullamco laboris. Lorem
                        ipsum dolor sit
                        amet cons aetetur adipisicing elit sedo eiusmod tempor.Incididunt labore et dolore magna aliqua.
                        sed ayd minim veniam.</p>
                    <p>Enimad minim veniam quis nostrud exercitation ullamco laboris. Lorem ipsum
                        dolor sit amet cons
                        aetetur adipisicing elit sedo eiusmod tempor.Incididunt labore et dolore magna aliqua. sed ayd
                        minim veniam.</p>
                </div>
                <!-- image container  -->
                <div class="image-responsive">
                    <img class="image-responsive" src="./../assets/sketch.png" alt="">
                </div>
            </div>
        </section>
        <!-- ---------------------apartmentsection ends here ----------------------- -->

        <!-- --------------------parallax with pop-up section starts here--------------------  -->
        <section class="parallax">
            <div class="pop-up-btn">
                <button class="btn-circle btn-center-align">
                    <span class="material-symbols-outlined">
                        play_arrow
                    </span>
                </button>
            </div>
        </section>
        <!-- --------------------parallax with pop-up  section ends here -------------------------- -->

        <!-- -----------------------Aminities  section starts here ------------------------- -->
        <section class="container py-4">
            <div class="text-center">
                <h5 class="sub-title">Our Aminities</h5>
                <h3 class="title">Building Aminities</h3>
            </div>
            <!-- container  -->
            <div class="medium-2 large-3 larger-4 gap-2">
                <!-- cards  -->
                <a class="aminities-card p-1" href="#">
                    <span class="icon">
                        <i class="material-icons">directions_car</i>
                    </span>
                    <h4 class="heading-4 my-2">Parking Space</h4>
                    <div class="arrow-btn">
                        <span class="material-symbols-outlined">
                            arrow_right_alt
                        </span>
                    </div>
                </a>
                <a class="aminities-card p-1" href="#">
                    <span class="icon">
                        <i class="material-icons">pool</i>
                    </span>
                    <h4 class="heading-4 my-2">Swimming Pool</h4>
                    <div class="arrow-btn">
                        <span class="material-symbols-outlined">
                            arrow_right_alt
                        </span>
                    </div>
                </a>
                <a class="aminities-card p-1" href="#">
                    <span class="icon">
                        <i class="material-icons">verified_user</i>
                    </span>
                    <h4 class="heading-4 my-2">Private Security</h4>
                    <div class="arrow-btn">
                        <span class="material-symbols-outlined">
                            arrow_right_alt
                        </span>
                    </div>
                </a>
                <a class="aminities-card p-1" href="#">
                    <span class="icon">
                        <i class="material-icons">house</i>
                    </span>
                    <h4 class="heading-4 my-2">Medical Center</h4>
                    <div class="arrow-btn">
                        <span class="material-symbols-outlined">
                            arrow_right_alt
                        </span>
                    </div>
                </a>
                <a class="aminities-card p-1" href="#">
                    <span class="icon">
                        <i class="material-icons">menu_book</i>
                    </span>
                    <h4 class="heading-4 my-2">Library Area</h4>
                    <div class="arrow-btn">
                        <span class="material-symbols-outlined">
                            arrow_right_alt
                        </span>
                    </div>
                </a>
                <a class="aminities-card p-1" href="#">
                    <span class="icon">
                        <i class="material-icons">king_bed</i>
                    </span>
                    <h4 class="heading-4 my-2">King Size Beds</h4>
                    <div class="arrow-btn">
                        <span class="material-symbols-outlined">
                            arrow_right_alt
                        </span>
                    </div>
                </a>
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
                <a class="aminities-card p-1" href="#">
                    <span class="icon">
                        <i class="material-icons">tune</i>
                    </span>
                    <h4 class="heading-4 my-2">Kid's Playland</h4>
                    <div class="arrow-btn">
                        <span class="material-symbols-outlined">
                            arrow_right_alt
                        </span>
                    </div>
                </a>
            </div>
        </section>
        <!----------------------- Aminities section ends here --------------------------- -->

        <!-- --------------------testimonials section starts here---------------------------->
        <section class="bg-dark py-4">
            <div id="testimonials" class="container">
                <div class="text-center">
                    <h5 class="sub-title">Our Testimonial</h5>
                    <h3 class="title">Clients Feedback</h3>
                </div>
                <!-- testimonials container  -->
                <div class="medium-2 large-3 gap-2">
                    <!-- cards  -->
                    <div class="testimonial">
                        <div class="mb-2">
                            <p class="text-light para-md-size"><span class="icon">
                                    <i class="material-icons">format_quote</i>
                                </span>
                                Precious ipsum dolor sit amet
                                consectetur adipisicing elit, sed dos
                                mod tempor incididunt ut labore et
                                dolore magna aliqua. Ut enim ad min
                                veniam, quis nostrud Precious ips
                                um dolor sit amet, consecte
                            </p>
                        </div>
                        <div class="flex align-center gap-1">
                            <img class="profile-rounded" src="./../assets/author.jpg" alt="profile">
                            <div>
                                <h5 class="text-dark">Adam Josheph</h5>
                                <p class="text-light">Selling Agent</p>
                            </div>
                        </div>
                    </div>
                    <div class="testimonial">
                        <div class="mb-2">
                            <p class="text-light para-md-size"><span class="icon">
                                    <i class="material-icons">format_quote</i>
                                </span>
                                Precious ipsum dolor sit amet
                                consectetur adipisicing elit, sed dos
                                mod tempor incididunt ut labore et
                                dolore magna aliqua. Ut enim ad min
                                veniam, quis nostrud Precious ips
                                um dolor sit amet, consecte
                            </p>
                        </div>
                        <div class="flex align-center gap-1">
                            <img class="profile-rounded" src="./../assets/author.jpg" alt="">
                            <div>
                                <h5 class="text-dark">Adam Josheph</h5>
                                <p class="text-light">Selling Agent</p>
                            </div>
                        </div>
                    </div>
                    <div class="testimonial">
                        <div class=" mb-2">
                            <p class="text-light para-md-size"><span class="icon">
                                    <i class="material-icons">format_quote</i>
                                </span>
                                Precious ipsum dolor sit amet
                                consectetur adipisicing elit, sed dos
                                mod tempor incididunt ut labore et
                                dolore magna aliqua. Ut enim ad min
                                veniam, quis nostrud Precious ips
                                um dolor sit amet, consecte
                            </p>
                        </div>
                        <div class="flex align-center gap-1">
                            <img class="profile-rounded" src="./../assets/author.jpg" alt="">
                            <div>
                                <h5 class="text-dark">Adam Josheph</h5>
                                <p class="text-light">Selling Agent</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </section>
        <!-- ----------------------testimonials section ends here ------------------------ -->

        <!----------------------------- blogs section starts here-----------------------  -->
        <section class="container py-4">
            <!-- section header  -->
            <div class="text-center">
                <h5 class="sub-title">News & Blogs</h5>
                <Title>Leatest News</Title>
                <h3 class="title">Leatest News Feeds</h3>
            </div>
            <!-- card container  -->
            <div class="medium-2 large-3 gap-2">
                <!-- individual card  -->
                <div class="blog-card">
                    <div class="relative card-image">
                        <a class="image-responsive" href="#">
                            <img class="image-responsive" src="./../assets/menu-banner-1.jpg" alt="">
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
                <div class="blog-card">
                    <div class="relative card-image">
                        <a class="image-responsive" href="#">
                            <img class="image-responsive" src="./../assets/menu-banner-1.jpg" alt="">
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
                <div class="blog-card">
                    <div class="relative card-image">
                        <a class="image-responsive" href="#">
                            <img class="image-responsive" src="./../assets/menu-banner-1.jpg" alt="">
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
            </div>
        </section>
        <!-- ------------------------blogs section ends here----------------------  -->
    </main>
    <!-- Main content ends here  -->
</template>
