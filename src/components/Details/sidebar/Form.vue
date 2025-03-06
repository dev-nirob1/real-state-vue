<template>
    <form>
        <label for="name"></label>
        <input type="text" id="name" placeholder="Your Name*">
        <label for="email"></label>
        <input type="text" id="email" placeholder="Your E-Mail*">
        <label for="message"></label>
        <textarea name="message" id="message" rows="6" placeholder="Write Message..."></textarea>
        <button class="btn btn-primary">Send Message</button>
    </form>
</template>

<style scoped>
input,
textarea {
    border: 2px solid var(--border-color);
    background-color: transparent;
    width: 100%;
    padding: 20px 10px;
    margin: 10px 0;
}
</style>