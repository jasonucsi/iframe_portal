<template>
  <div class="banner">
    <vueper-slides :slide-ratio="1 / 4" :arrows="false" :bullets="false" autoplay>
      <vueper-slide
        v-for="(slide, i) in slides"
        :key="i"
        :image="slide.image"
      >
      </vueper-slide>
    </vueper-slides>
  </div>
</template>

<script>
import { VueperSlides, VueperSlide } from 'vueperslides';
import 'vueperslides/dist/vueperslides.css';

export default {
  name: 'CarouselPage',
  components: {
    VueperSlides,
    VueperSlide
  },
  data() {
    return {
      // breakpoints: {
      //   600: {
      //     slideRatio: 2/3
      //   }
      // },
      slides: [
        {
          title: 'Slide #1',
          content: 'Slide 1 content.',
          image: require('../assets/carousel-1.jpg')
        },
        {
          title: 'Slide #2',
          content: 'Slide 2 content.',
          image: require('../assets/carousel-2.jpg')
        },
        {
          title: 'Slide #3',
          content: 'Slide 3 content.',
          image: require('../assets/carousel-3.jpg')
        }
      ]
    };
  }
};
</script>

<style scoped>
.banner {
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  overflow: hidden;
  z-index: 1;
}

.vueper-slide {
  position: relative;
  width: 100%;
  height: 100%;
}

.vueper-slide img {
  width: 100%;
  height: 100%;
  object-fit: contain; /* Change to contain to prevent cropping */
  object-position: center;
  max-width: 100%; /* Add max-width to prevent horizontal overflow */
  max-height: 100vh; /* Add max-height to prevent vertical overflow */
}
</style>


