<template>
    <div>
        <footer class="footer-area">
            <div class="container">         

                <div class="copyright-area">
                    <p>Copyright @2024 Paymi. All rights reserved <router-link  to="/">Paymi Solutions Limited</router-link></p>
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