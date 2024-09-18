<template>
<div class="wrapper">
    <CarouselPage/>
    <AnnouncementPage/>
  </div>
</template>

<script>
import CarouselPage from './components/Carousel.vue'
import AnnouncementPage from './components/Announcement.vue'

export default {
  name: 'App',
  compatConfig: {
    INSTANCE_LISTENERS: false,
  },
  components: {
    CarouselPage,
    AnnouncementPage
  }
}
</script>

<style>
.wrapper {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 500px; */
}
</style>
