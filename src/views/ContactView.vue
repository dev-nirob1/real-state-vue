<script setup>
import AddressCard from '@/components/Contact/AddressCard.vue';
import ContactForm from '@/components/Contact/ContactForm.vue';
import Map from '@/components/Contact/Map.vue';
import PageTitle from '@/components/shared/PageTitle.vue';

</script>

<template>
   <PageTitle>Contact Us</PageTitle>

    <!-- contact address section  -->
    <div class="container py-4">
        <div class="medium-2 large-3 gap-2">
            <AddressCard/>
            <AddressCard/>
            <AddressCard/>
        </div>
    </div>
    <!-- contact address section  -->

    <!-- form with map section  -->
    <div class="contact-form-map mb-2">
        <section class="container pb-4">
            <ContactForm/>
        </section>
        <Map></Map>
    </div>
    <!-- form with map section  -->
</template>
