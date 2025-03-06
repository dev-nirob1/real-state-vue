<script setup>
import Map from '@/components/Contact/Map.vue';
import Features from '@/components/Details/Features.vue';
import FloorPlans from '@/components/Details/FloorPlans.vue';
import Gallery from '@/components/Details/Gallery.vue';
import PropertyDetails from '@/components/Details/PropertyDetails.vue';
import Form from '@/components/Details/sidebar/Form.vue';
import TopProducts from '@/components/Details/sidebar/TopProducts.vue';
import Slider from '@/components/Details/Slider.vue';
import PropertiesCard from '@/components/shared/PropertiesCard.vue';

</script>
<template>
    <!-- page title  -->
    <div class="bg-dark">
        <div class="container page-title">
            <h3 class="title">Scion Hasnat Villa</h3>
            <p class="flex align-center text-light font-bold"><span class="material-symbols-outlined primary-color">
                    home
                </span>House - 24, Road - 01</p>
        </div>
    </div>
    <!-- slider  -->
    <Slider />

    <div class="details-container large-3 justify-center container">
        <div class="details span-2">
            <!-- property features  -->
            <div class="small-2 large-3 larger-4 gap-2">
                <Features/>
                <Features/>
                <Features/>
                <Features/>
                <Features/>
                <Features/>
                <Features/> 
                <Features/> 
            </div>
            <!-- property details  -->
            <div class="text-light">
                <h4 class="heading">Property Detail</h4>
                <PropertyDetails/>
            </div>
            <!-- gallary  -->
            <div>
                <h4 class="heading">From Our Gellary</h4>
                <Gallery/>
            </div>
            <!-- floor plan tab  -->
            <div>
                <h4 class="heading">Floor Plans</h4>
                <div class="flex align-center flex-wrap para-md-size font-bold text-light gap-1 mb-4">
                    <p>First Floor</p>
                    <p>Second Floor</p>
                    <p>Third Floor</p>
                    <p> Top Garden</p>
                </div>
                <div class="medium-2 gap-2">
                    <FloorPlans/>
                </div>
            </div>
            <!-- property video  -->
            <div>
                <h4 class="heading">Property Video</h4>
                <div class="video-bg-image">
                    <button class="btn-circle btn-center-align">
                        <span class="material-symbols-outlined">
                            play_arrow
                        </span>
                    </button>
                </div>
            </div>
            <!-- map  -->
            <div>
                <h4 class="heading">Location</h4>
               <Map/>
            </div>
            <!-- related properties  -->
            <div>
                <h4 class="heading">Related Properties</h4>
                <div class="medium-2 gap-2">
                    <PropertiesCard/>
                    <PropertiesCard/>
                </div>
            </div>
        </div>
        <!-- right side box  -->
        <aside class="sidebar">
            <!-- form  -->
            <div>
                <h4 class="heading">Drop Messege For Book</h4>
                <Form/>
            </div>
            <!-- top rated products  -->
            <div>
                <h4 class="heading">Top Rated Product</h4>
                <!-- card  -->
                <TopProducts/>
                <TopProducts/>
            </div>

            <!-- Social media links  -->
            <div>
                <h4 class="heading">Follow us</h4>
                <div class="flex gap-1 items-center social-link">
                    <a href="#">
                        <span class="material-symbols-outlined">book</span>
                    </a>
                    <a href="#">
                        <span class="material-symbols-outlined">book</span>
                    </a>
                    <a href="#">
                        <span class="material-symbols-outlined">book</span>
                    </a>
                </div>
            </div>
        </aside>
    </div>
</template>

<style scoped>
/* common  */
.link:hover {
    color: var(--primary-color);
    transition: color .3s ease-in-out;
}

.heading {
    padding-left: .5rem;
    margin-bottom: 1rem;
    border-left: 2px solid var(--primary-color);
}

.video-bg-image {
    position: relative;
    background-image: url('../assets/about-4.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    height: 50vh;
}

.location-icon {
    color: var(--primary-color);
}

/* ---------sidbar starts--------------- */
.sidebar {
    width: 100%;
    margin: 0 auto
}

.sidebar>div {
    padding: 1rem;
    margin-bottom: 2rem;
    border: 2px solid var(--border-color);
}

.social-link a {
    color: var(--primary-color);
    background-color: var(--bg-light);
    height: 2.5rem;
    width: 2.5rem;
    display: flex;
    align-items: center;
    justify-content: center;
}

/* ---------sidbar ends--------------- */
.details>div {
    margin-bottom: 3rem;
}

 .details h4 {
    color: var(--dark-color);
}

 .details p {
    color: var(--text-light-color);
    font-weight: 500;
}  


@media (min-width: 992px) {
    .sidebar {
        padding-left: 0;
    }

    .details-container {
        padding: 3rem 0;
        gap: 2rem;
    }

    .video-bg-image {
        height: 80vh;
    }

    .sidebar>div {
        margin-bottom: 3rem;
    }
}
</style>