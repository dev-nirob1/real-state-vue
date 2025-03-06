<template>
    <div class="contact-form">
                <h4 class="heading-4 mb-1">Get A Quote</h4>
                <form>
                    <div class="medium-2 align-center gap-2">
                        <div>
                            <label for="name"></label>
                            <input id="name" type="text" placeholder="Enter Your Name">
                        </div>
                        <div>
                            <label for="email"></label>
                            <input id="email" type="email" placeholder="Enter Your Email">
                        </div>
                        <div>
                            <label for="select-services"></label>
                            <select id="select-services">
                                <option value="Select Service Type" selected disabled>Select Service Type</option>
                                <option value="Property Management">Property Management</option>
                                <option value="Mortgage Service">Mortgage Service</option>
                                <option value="Consulting Service">Consulting Service</option>
                            </select>
                        </div>
                        <div>
                            <label for="phone"></label>
                            <input type="tel" id="phone" placeholder="Enter Your Phone Number">
                        </div>
                    </div>
                    <div class="my-2">
                        <label for="message"></label>
                        <textarea rows="6" id="message" placeholder="Enter Message..."></textarea>
                    </div>
                    <div class="flex gap-1">
                        <div>
                            <label for="checkbox"></label>
                            <input type="checkbox" id="checkbox">
                        </div>
                        <p> Save my name, email, and website in this browser for the next time I comment.
                        </p>
                    </div>
                    <button class="btn btn-primary mt-2">GET A FREE SERVICE</button>
                </form>
            </div>
</template>
<style scoped>
.contact-form {
    padding: 1rem;
    border: 1px solid var(--border-color);
    background-color: var(--secondary-color);
    z-index: 999;
}

.contact-form form input,
select,
textarea {
    position: relative;
    width: 100%;
    padding: 20px;
    border: 2px solid var(--border-color);
}

@media (min-width: 992px) {
    .contact-form {
        padding: 2rem;
    }
}
</style>