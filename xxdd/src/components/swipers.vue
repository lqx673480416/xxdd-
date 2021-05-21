<template>
    <div class="swiper-container pctswiper">
        <div class="swiper-wrapper">
            <slot></slot>
        </div>
    </div>
</template>

<script>
import Swiper from 'swiper';
export default {
    mounted() {
        new Swiper(".pctswiper",{
            loop:true,
            autoplay:{
                delay:2000,
                disableOnInteraction:false,
            }
        })
    },
}
</script>