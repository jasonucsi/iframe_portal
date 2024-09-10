<template>
  <div class="banner">
    <vueper-slides  :arrows="false" :bullets="false" autoplay>
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
  position: fixed; /* Fixed positioning to cover the entire viewport */
  top: 0;
  left: 0;
  width: 100vw; /* Full viewport width */
  height: 100vh; /* Full viewport height */
  overflow: hidden; /* Hide any overflow */
}

.vueper-slide {
  position: relative;
  width: 100%;
  height: 100%;
}

.vueper-slide img {
  width: 100%;
  height: 100%;
  object-fit: cover; /* Ensure the image covers the container without distortion */
  object-position: center; /* Center the image within the container */
  border-radius: 50%; /* Make the image circular */
}
</style>

