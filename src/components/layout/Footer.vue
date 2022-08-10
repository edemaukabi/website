<template>
    <div>
        <footer class="footer-area">
            <div class="container">
                <div class="row">
                    <div class="col-lg-4 col-sm-6 col-md-6">
                        <div class="single-footer-widget">
                            <div class="logo">
                                <router-link to="/"><img src="../../assets/images/pay color.png" alt="logo"></router-link>
                                <p>We are a payment enablement company focused on facilitating seamless payments between individual consumers, organizations and business enterprises.</p>
                            </div>
                            <ul class="social-links">
                                <li><a href="https://twitter.com/youcanpayos" target="_blank"><i class="fab fa-twitter"></i></a></li>
                                <li><a href="https://www.instagram.com/youcanpayos/" target="_blank"><i class="fab fa-instagram"></i></a></li>
                            </ul>
                        </div>
                    </div>

                    <div class="col-lg-4 col-sm-6 col-md-6">
                        <div class="single-footer-widget pl-5">
                            <h3>Our Services</h3>

                            <ul class="list">
                                <li>POS devices & card readers</li>
                                <li>Withdrawals & deposits</li>
                                <li>Enterprise integration</li>
                                <li>Secure payments</li>
                                <!-- <li><router-link to="/#">Latest News</router-link></li> -->
                            </ul>
                        </div>
                    </div>

                    <!-- <div class="col-lg-3 col-sm-6 col-md-6">
                        <div class="single-footer-widget">
                            <h3>Support</h3>

                            <ul class="list">
                                <li><router-link to="/faq">FAQ's</router-link></li>
                                <li><router-link to="/privacy-policy">Privacy Policy</router-link></li>
                                <li><router-link to="/terms-condition">Terms & Condition</router-link></li>
                                <li><router-link to="/#">Community</router-link></li>
                                <li><router-link to="/contact">Contact Us</router-link></li>
                            </ul>
                        </div>
                    </div> -->

                    <div class="col-lg-4 col-sm-6 col-md-6">
                        <div class="single-footer-widget">
                            <h3>Contact Info</h3>

                            <ul class="footer-contact-info">
                                <li><span>Location:</span>36, Nouckachott Avenue, zone 1, Wuse, Abuja.</li>
                                <li><span>Email:</span> <a href="mailto:Projects@paymi.com.ng">Projects@paymi.com.ng</a></li>
                                <li><span>Phone:</span> <a href="tel:+2348033445507">+2348033445507</a></li>
                            </ul>
                        </div>
                    </div>
                </div>

                <div class="copyright-area">
                    <p>Copyright @2022 PayOS. All rights reserved <a href="http://smadeandsmight.com/" target="_blank">SmadeandSmight.com</a></p>
                </div>
            </div>

            <div class="map-image"><img src="../../assets/images/map.png" alt="map"></div>
        </footer>
        <!-- End Footer Area -->

        <back-to-top bottom="50px" right="50px">
            <div class="go-top">
                <i class="fas fa-arrow-up"></i>
            </div>
        </back-to-top>
    </div>
</template>

<script>
    export default {
        name: 'Footer'
    }
</script>