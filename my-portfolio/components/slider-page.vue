<template>
<div>
    <container>
        <template v-slot:content>
            <swiper autoplay :pagination="true" :modules="modules" class="w-full h-full" >
                <swiper-slide><page-one/></swiper-slide>
                <swiper-slide><page-two/></swiper-slide><swiper-slide><page-three/></swiper-slide>
                <swiper-slide>Slide 4</swiper-slide><swiper-slide>Slide 5</swiper-slide>
                <swiper-slide>Slide 6</swiper-slide><swiper-slide>Slide 7</swiper-slide>
                <swiper-slide>Slide 8</swiper-slide><swiper-slide>Slide 9</swiper-slide>
            </swiper>
        </template>
    </container>
</div>
</template>
<script>
  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from 'swiper/vue';

  // Import Swiper styles
  import 'swiper/css';

  import 'swiper/css/pagination';

  // import required modules
  import { Pagination, Autoplay } from 'swiper';

  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    setup() {
      return {
        modules: [Pagination, Autoplay],
      };
    },
  };
</script>
