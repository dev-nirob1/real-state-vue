<template>
     <!-- page title  -->
     <div class="bg-dark">
        <div class="container page-title">
            <h3 class="title">Contact Us</h3>
            <p><span class="material-symbols-outlined primary-color">
                    home
                </span> <a href="#">Home</a> <span class="material-symbols-outlined">
                    chevron_right
                </span> <span>Contact Us</span></p>
        </div>
    </div>

    <div class="tab-panel-container container medium-3">
        <ul class="medium-span-2 flex flex-wrap gap-1 tab-panel">
            <li><a class="active" href="#">All</a></li>
            <li><a href="#">ONGoing</a></li>
            <li><a href="#">Completed</a></li>
            <li><a href="#">Upcoming</a></li>
        </ul>
        <div class="dropdown-container flex align-center">
            <label for="location">Location: </label>
            <select name="location" id="location">
                <option value="Please Select" selected disabled>Please Select</option>
                <option value="'Dhaka">Dhaka</option>
            </select>
        </div>
    </div>
    <section class="p-4">
        <div class="medium-2 large-3 gap-2">
            <div class="properties-card">
                <div class="relative image-responsive">
                    <img class="image-responsive" src="../assets/about-3.jpg" alt="">
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
            <div class="properties-card">
                <div class="relative image-responsive">
                    <img class="image-responsive" src="../assets/about-3.jpg" alt="">
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
            <div class="properties-card">
                <div class="relative image-responsive">
                    <img class="image-responsive" src="../assets/about-3.jpg" alt="">
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
        </div>
    </section>
</template>

<style scoped>
.tab-panel-container {
    padding: var(--tab-panel-padding);
}

.tab-panel {
    margin: 2rem 0;
}

.tab-panel li{
    margin-bottom: 1rem;
}

.tab-panel li a {
    padding: var(--btn-padding);
    border: 1px solid var(--border-color);
}

.active {
    background-color: #000;
    color: var(--secondary-color);
}

.dropdown-container select {
    margin-left: .5rem;
    padding: .5rem;
}
</style>