<script setup lang="ts">
import SubTitle from '../shared/SubTitle.vue';
import Title from '../shared/Title.vue';

</script>

<template>
      <section class="container py-4">
            <div class="large-2 align-center gap-2">
                <!-- image div  -->
                <div class="image-responsive relative">
                    <img class="image-responsive" src="./../../assets/about-us-1.png" alt="image">
                    <div class="video-image">
                        <div class="image-responsive relative">
                            <img class="image-responsive" src="./../../assets/about-us-2.png" alt="image">
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
                        <SubTitle>
                            About Us
                        </SubTitle>
                        <Title>
                            The Leading Real Estate Rental Marketplace.
                        </Title>
                    </div>
                    <!-- section header div ends -->
                    <p class="text-light mb-1">Over 39,000 people work for us in more than 70 countries
                        all over the
                        This breadth of global
                        coverage, combined with specialist services
                    </p>
                    <!-- icon + title container  -->
                    <div class="all-2 align-center text-light">
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
                    <p class="about-quote text-light">
                        "Enimad minim veniam quis nostrud exercitation
                        llamco laboris. Lorem ipsum dolor sit amet"
                    </p>
                    <button class="btn btn-primary">OUR SERVICES</button>
                </div>
            </div>
        </section>
</template>

<style scoped>
.video-image {
  width: 150px;
  position: absolute;
  bottom: 100px;
}

.about-icons {
  background-color: var(--bg-light);
  color: var(--primary-color);
  height: 2.5rem;
  width: 2.5rem;
  border-radius: 50%;
  margin-right: 1rem;
}

.about-quote {
  padding: 2rem;
  margin: 2rem 0;
  background-color: var(--bg-light);
  border-left: 5px solid var(--primary-color);
  font-weight: 300;
}
@media (min-width: 768px) {
    .video-image {
          width: 300px;
          position: absolute;
          bottom: 100px;
      }
}
</style>