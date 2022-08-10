<template>
    <div class="partner-area-two ptb-70">
        <div class="container">
            <div class="partner-slider owl-carousel owl-theme">
                <carousel
                    :autoplay = "true"
                    :loop = "true"
                    :paginationEnabled = "false"
                    :autoplaySpeed = "true"
                    :autoplayTimeout = "5000"
                    :perPageCustom = "[[0, 1], [576, 1], [768, 3], [1024, 4], [1200, 5]]"
                >
                    <slide v-for="item in carouselItems" :key="item.id">
                        <div class="single-partner-item">
                            <img :src="item.image" alt="image">
                        </div>
                    </slide>
                </carousel>
            </div>
        </div>
    </div>
</template>

<script>
import { Carousel, Slide } from 'vue-carousel'
import image1 from '../../assets/images/partner/logo hangout.png'
import image2 from '../../assets/images/partner/bankeasy-dark.png'
import image3 from '../../assets/images/partner/0e55ea74-4066-4b87-91ea-f1c56c0ce414.png'
import image4 from '../../assets/images/partner/2693bb1a-0d0b-4a6c-8f5e-62bc5be350a7.png'
import image5 from '../../assets/images/partner/Nipost.png'

export default {
    name: 'Partner',
    components: {
        Carousel,
        Slide
    },
    data() {
        return {
            carouselItems: [
                {
                    id: 1,
                    image: image1,
                },
                {
                    id: 2,
                    image: image2,
                },
                {
                    id: 3,
                    image: image3,
                },
                {
                    id: 4,
                    image: image4,
                },
                {
                    id: 5,
                    image: image5,
                },
            ]
        }
    }
}
</script>