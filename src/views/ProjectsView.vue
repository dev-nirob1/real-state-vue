<script setup lang="ts">
import PageTitle from '@/components/shared/PageTitle.vue';
import PropertiesCard from '@/components/shared/PropertiesCard.vue';
import Title from '@/components/shared/Title.vue';

</script>

<template>
    <!-- page title  -->
    <PageTitle>
        Projects
    </PageTitle>

    <div class="tab-panel-container container medium-3">
        <ul class="medium-span-2 flex flex-wrap gap-1 tab-panel">
            <li><a class="active" href="#">All</a></li>
            <li><a href="#">Ongoing</a></li>
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
            <PropertiesCard/>
            <PropertiesCard/>
            <PropertiesCard/>
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

.tab-panel li {
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