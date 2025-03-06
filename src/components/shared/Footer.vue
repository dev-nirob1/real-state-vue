<template>
    <!-- call to action section  -->
    <div class="cta-wrapper">
        <div class="call-to-action">
            <div class="cta flex align-center items-center justify-between">
                <div class="">
                    <h3 class="title mb-1">Looking for a dream home?</h3>
                    <p class="">
                        We help you make the dream of new house a reality
                    </p>
                </div>
                <button class="btn cta-btn">Explore Properties</button>
            </div>
        </div>
    </div>

    <!-- footer starts here  -->
    <footer>
        <div class="small-2 medium-2 larger-5 wrapper gap-1">
            <!-- contact info -->
            <div>
                <img class="mb-1" src="./../../assets/footer-logo.png" alt="logo">
                <p class="mb-1">Lorem Ipsum is simply dummy text of the and typesetting industry. Lorem Ipsum is
                    dummy
                    text of the
                    printing.</p>
                <div class="flex align-center gap-1">
                    <span class="material-symbols-outlined">
                        location_on
                    </span>
                    <p>Brooklyn, New York, United States</p>
                </div>
                <div class="flex align-center gap-1">
                    <span class="material-symbols-outlined">
                        phone_in_talk
                    </span>
                    <p>+0123-456789</p>
                </div>
                <div class="flex align-center gap-1">
                    <span class="material-symbols-outlined">
                        mail
                    </span> example@example.com
                </div>
            </div>
            <!-- contact info ends  -->

            <!-- company with links -->
            <div class="mb-2">
                <h4 class="heading-4 mb-1">Company</h4>
                <ul class="footer-links">
                    <li><a href="#">About</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">All Products</a></li>
                    <li><a href="#">Location Maps</a></li>
                    <li><a href="#">FAQ</a></li>
                    <li><a href="#">Contact us</a></li>
                </ul>
            </div>
            <div class="mb-2">
                <h4 class="heading-4 mb-1">Services</h4>
                <ul class="footer-links">
                    <li><a href="#">Order tracking</a></li>
                    <li><a href="#">Wish List</a></li>
                    <li><a href="#">Login</a></li>
                    <li><a href="#">My account</a></li>
                    <li><a href="#">Terms & Conditions</a></li>
                    <li><a href="#">Promotional Offers</a></li>
                </ul>
            </div>
            <div class="mb-2">
                <h4 class="heading-4 mb-1">Customer care</h4>
                <ul class="footer-links">
                    <li><a href="#">Login</a></li>
                    <li><a href="#">My account</a></li>
                    <li><a href="#">Wish List</a></li>
                    <li><a href="#">Order Tracking</a></li>
                    <li><a href="#">FAQ</a></li>
                    <li><a href="#">Contact us</a></li>
                </ul>
            </div>
            <div class="mb-2">
                <div class="newsletter mb-1">
                    <h4 class="heading-4">NewsLetter</h4>
                    <p class="my-1">Subscribe to our weekly Newsletter and receive updates via email.</p>
                    <div class="flex items-center">
                        <input type="text" placeholder="Email">
                        <button class="footer-btn">Send</button>
                    </div>
                </div>
                <div>
                    <h4 class="mb-1">We Accept</h4>
                    <img class="image-responsive" src="./../../assets/payment-4.png" alt="payment image">
                </div>
            </div>
        </div>

        <div class="footer-bottom body-font-family">
            <p>All Rights Reserved @ Company 2025</p>
            <ul>
                <li>
                    <a href="#">Terms & Conditions</a>
                </li>
                <li>
                    <a href="#">Claim</a>
                </li>
                <li>
                    <a href="#">Privacy & Policy</a>
                </li>
            </ul>
        </div>
    </footer>
    <!-- footer ends here  -->
</template>
<style scoped>
.cta-wrapper {
  position: relative;
  margin-top: 10rem;
}

.call-to-action {
  padding: 3rem;
  background-color: var(--footer-bg);
}

.cta {
  flex-direction: column;
  gap: 2rem;
  width: 90%;
  max-width: 1340px;
  color: var(--secondary-color);
  background-color: var(--primary-color);
  padding: var(--cta-padding);
  font-family: var(--nunito-font);
  position: absolute;
  left: 50%;
  top: 0;
  z-index: 1;
  transform: translate(-50%, -50%);
}
footer {
    font-family: var(--popins-font);
    background-color: var(--footer-bg);
    color: var(--secondary-color);
    position: relative;
}

.wrapper {
    padding: var(--footer-wrapper);
}

.footer-links li:not(:last-child) {
    margin-bottom: 1rem;
}

.footer-links li {
    position: relative;
    transition: color 0.3s ease-in-out;
}

.footer-links li:hover {
    color: var(--primary-color);
}

.footer-links li::before {
    content: "//";
    position: absolute;
    left: -1rem;
    font-size: 16px;
    color: transparent;
    transition: color 0.3s ease-in-out, content 0.3s ease-in-out;
}

.footer-links li:hover::before {
    content: "//";
    color: var(--primary-color);
}

.newsletter input {
    padding: 1rem;
    background-color: var(--secondary-color);
    outline: none;
    border: none;
    border: 1px solid var(--border-color);
}

.footer-btn {
    padding: 1rem 2rem;
    outline: none;
    border: none;
    color: var(--secondary-color);
    background-color: var(--primary-color);
}

.footer-bottom {
    background-color: var(--bottom-footer-bg);
    padding: 1rem;
    display: flex;
    flex-direction: column;
    gap: 1rem;
    text-align: center;
    align-items: center;
    justify-content: space-between;
}

.footer-bottom ul {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 1rem;
}

@media (min-width: 992px) {
    .cta {
        flex-direction: row;
    }

    .footer-bottom {
        flex-direction: row;
    }
}
</style>