<template>
<div class="wrapper">
    <!-- <CarouselPage/> -->
    <!-- <AnnouncementPage/> -->
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
  <div class="announcement">
    <div class="title">
      <h1>Announcement</h1>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/announcement1.jpg" alt="Image" class="image" @click="onClickImage1()">
          <div class="text-content">
            <h3>10-September-2024 03:10pm</h3>
            <p>
              Deadline of Apply for Supplementary Exam (May-Aug) 2024 Semester
            </p>
          </div>
        </li>
      </ul>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/default.jpg" alt="Image" class="image"  @click="onClickImage2()">
          <div class="text-content">
            <h3>08-September-2024 09:30am</h3>
            <p>
              SARAWAK CAMPUS MASTER CLASS TIMETABLE SEMESTER 2024-09 - Draft 3

              Dear students,

              Kindly find the attached Master Class Timetable for Semester 2024-09 (Sarawak Campus) – Draft 3 for your reference.

              Should there any clashes identified, kindly inform your respective faculty latest by 

              11th September 2024, 12.00pm

              For any enquiries regarding to the Master Class Timetable, please proceed to the respective Faculty Administrator :

              Faculty of Hospitality and Tourism Management - Ms. Ivy Irvine Mikal , ivyirvine@ucsiuniversity.edu.my

              Faculty of Business & Management & Centre For Pre-U Studies - Ms. Felicia Anak Girim , feliciaag@ucsiuniversity.edu.my
            </p>
          </div>
        </li>
      </ul>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/announcement2.jpg" alt="Image" class="image"  @click="onClickImage3()">
          <div class="text-content">
            <h3>26-August -2024 09:38am</h3>
            <p>
              REGISTRAR’S OFFICE: ANNOUNCEMENT OF UCSI UNIVERSITY 37th CONVOCATION CEREMONY YEAR 2024 SEPTEMBER EDITION
            </p>
          </div>
        </li>
      </ul>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/coffee.jpg" alt="Image" class="image"  @click="onClickImage4()">
          <div class="text-content">
            <h3>14-June -2024 11:42am</h3>
            <p>
              🌟 Sip & Share: Coffee Break 🌟

              📅 Date: Every Alternate Thursdays
              🕒 Time: 4:00 PM – 6:00 PM
              📍 Location: Postgraduate Lounge, Level 10, Block G, KL Campus
              🎉 Extras: Free coffee, snacks, and fun sharing! 

              

              💡 Why You Can’t Miss This:

              Unlock Your Potential: Discover why UCSI is your best choice for progression.
              Get Expert Advice: Personalized guidance on programs tailored to your interests.
              Career Pathways: Explore the best career options and pathways available to you.
              Simplify Admissions: Understand the progression admission process inside out.
              Network & Chill: Meet fellow students and make new friends in a relaxed setting.
              🔹 Secure Your Spot Now:  https://shorturl.at/4vjH2
            </p>
          </div>
        </li>
      </ul>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/honours.jpg" alt="Image" class="image"  @click="onClickImage5()">
          <div class="text-content">
            <h3>22-June -2023 11:45am</h3>
            <p>
              CALLING ALL FIRST-CLASS HONOURS GRADUATES

              Dear UCSIans, 

              Visit us at Student Enrolment Centre, Block G Level 1 to find out more!
            </p>
          </div>
        </li>
      </ul>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/whatsnext.jpg" alt="Image" class="image"  @click="onClickImage6()">
          <div class="text-content">
            <h3>14-March -2024 09:11am</h3>
            <p>
              Be what’s next with a UCSI degree.

              Dear UCSIans, 

              Visit us at Student Enrolment Centre, Block G Level 1 to find out more!

            </p>
          </div>
        </li>
      </ul>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/boost.jpg" alt="Image" class="image"  @click="onClickImage7()">
          <div class="text-content">
            <h3>14-March -2024 08:19am</h3>
            <p>
              Boost your Career. Go Postgrad

              Dear UCSIans, 

              Visit us at Student Enrolment Centre, Block G Level 1 to find out more!

            </p>
          </div>
        </li>
      </ul>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/diet.jpg" alt="Image" class="image"  @click="onClickImage8()">
          <div class="text-content">
            <h3>14-March -2024 08:19am</h3>
            <p>
              Dietitian.
            </p>
          </div>
        </li>
      </ul>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/contact.jpg" alt="Image" class="image"  @click="onClickImage9()">
          <div class="text-content">
            <h3>14-March -2024 08:19am</h3>
            <p>
              Contact Us - Examination Centre

              For more information or any enquiries, you may click on the image.
            </p>
          </div>
        </li>
      </ul>
    </div>
  </div>
  </div>
</template>

<script>
// import CarouselPage from './components/Carousel.vue'
// import AnnouncementPage from './components/Announcement.vue'
import { VueperSlides, VueperSlide } from 'vueperslides';
import 'vueperslides/dist/vueperslides.css';
import Swal from "sweetalert2";

export default {
  name: 'App',
  compatConfig: {
    INSTANCE_LISTENERS: false,
  },
  components: {
    // CarouselPage,
    // AnnouncementPage
    VueperSlides,
    VueperSlide
  },
  data() {
    return {
      slides: [
        {
          title: 'Slide #1',
          content: 'Slide 1 content.',
          image: require('./assets/carousel-1.jpg')
        },
        {
          title: 'Slide #2',
          content: 'Slide 2 content.',
          image: require('./assets/carousel-2.jpg')
        },
        {
          title: 'Slide #3',
          content: 'Slide 3 content.',
          image: require('./assets/carousel-3.jpg')
        }
      ]
    };
  },
  methods: {
    onClickImage1(){
    const imageUrl = require('./assets/announcement1.jpg')
      Swal.fire({
        imageUrl: imageUrl,
        imageWidth: 300,
        imageHeight: 400,
        imageAlt: "Custom image",
        confirmButtonText: 'OK',
        confirmButtonColor: '#FF0000', // change the OK button color to red
      });
    },
    onClickImage2(){
    const imageUrl = require('./assets/default.jpg')
      Swal.fire({
        imageUrl: imageUrl,
        imageWidth: 300,
        imageHeight: 400,
        imageAlt: "Custom image",
        confirmButtonText: 'OK',
        confirmButtonColor: '#FF0000', // change the OK button color to red
      });
    },
    onClickImage3(){
    const imageUrl = require('./assets/announcement2.jpg')
      Swal.fire({
        imageUrl: imageUrl,
        imageWidth: 300,
        imageHeight: 400,
        imageAlt: "Custom image",
        confirmButtonText: 'OK',
        confirmButtonColor: '#FF0000', // change the OK button color to red
      });
    },
    onClickImage4(){
    const imageUrl = require('./assets/coffee.jpg')
      Swal.fire({
        imageUrl: imageUrl,
        imageWidth: 300,
        imageHeight: 400,
        imageAlt: "Custom image",
        confirmButtonText: 'OK',
        confirmButtonColor: '#FF0000', // change the OK button color to red
      });
    },
    onClickImage5(){
    const imageUrl = require('./assets/honours.jpg')
      Swal.fire({
        imageUrl: imageUrl,
        imageWidth: 300,
        imageHeight: 400,
        imageAlt: "Custom image",
        confirmButtonText: 'OK',
        confirmButtonColor: '#FF0000', // change the OK button color to red
      });
    },
    onClickImage6(){
    const imageUrl = require('./assets/whatsnext.jpg')
      Swal.fire({
        imageUrl: imageUrl,
        imageWidth: 300,
        imageHeight: 400,
        imageAlt: "Custom image",
        confirmButtonText: 'OK',
        confirmButtonColor: '#FF0000', // change the OK button color to red
      });
    },
    onClickImage7(){
    const imageUrl = require('./assets/boost.jpg')
      Swal.fire({
        imageUrl: imageUrl,
        imageWidth: 300,
        imageHeight: 400,
        imageAlt: "Custom image",
        confirmButtonText: 'OK',
        confirmButtonColor: '#FF0000', // change the OK button color to red
      });
    },
    onClickImage8(){
    const imageUrl = require('./assets/diet.jpg')
      Swal.fire({
        imageUrl: imageUrl,
        imageWidth: 300,
        imageHeight: 400,
        imageAlt: "Custom image",
        confirmButtonText: 'OK',
        confirmButtonColor: '#FF0000', // change the OK button color to red
      });
    },
    onClickImage9(){
    const imageUrl = require('./assets/contact.jpg')
      Swal.fire({
        imageUrl: imageUrl,
        imageWidth: 300,
        imageHeight: 400,
        imageAlt: "Custom image",
        confirmButtonText: 'OK',
        confirmButtonColor: '#FF0000', // change the OK button color to red
      });
    },
  }
}
</script>

<style>
.wrapper {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
}

/* .banner {
  position: fixed; 
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh; 
  overflow: hidden; 
  z-index: 0; 
}

.announcement {
  position: relative; 
  z-index: 1; 
  margin-top: 25%; 
  padding: 20px;
} */

.banner {
 /* Keep this to ensure the banner is at the top */
  /*position: fixed*/
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh; /* Full height of the viewport */
  overflow: hidden; /* Hide any overflow */
  z-index: 1; /* Ensure the banner is above other content */
}

.announcement {
  position: relative;
  margin-top: -65vh; /* Reduce this value to move it closer */
  padding: 20px;
  z-index: 2;
  background-color: #fff; /* Ensure a solid background */
}


.title {
  display: flex;
  justify-content: center;
}

.paragraph-container {
  display: flex;
  flex-direction: column;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  margin-bottom: 20px;
  display: flex;
  align-items: flex-start;
}

.image {
  max-width: 50px;
  max-height: 50px;
  margin-right: 20px;
  object-fit: cover;
}

.text-content {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

h3 {
  margin: 0;
}

p {
  margin: 0;
  text-align: justify;
}
</style>
