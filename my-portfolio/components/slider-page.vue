<template>
<div>
    <container>
        <template v-slot:content>
            <swiper autoplay :pagination="true" :modules="modules" class="w-full h-full" >
                <swiper-slide><page-one/></swiper-slide>
                <swiper-slide><page-two/></swiper-slide>
                <swiper-slide><page-three/></swiper-slide>
                <swiper-slide>
                    <div class="flex flex-col justify-center items-center h-full">
                    <h2 class="md:text-[40px] tracking-[3px] uppercase font-bold">Projects</h2>
                    <h2 class="md:text-[20px] tracking-[3px] uppercase font-light text-center md:w-10/12">Note: Most of my experience(s) as a front-end developer and a ui/ux designer were acquired working on contract &amp; freelance projects.</h2>
                    <br>
                    <br>
                    <br>
                    </div>
                </swiper-slide>
                <swiper-slide><page-four/></swiper-slide>
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
