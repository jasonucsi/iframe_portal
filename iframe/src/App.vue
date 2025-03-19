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
          <img src="./assets/default.jpg" alt="Image" class="image"  @click="onClickImage2()">
          <div class="text-content">
            <h3>18-March -2025 02:22pm</h3>
            <p>
              Sarawak Campus Final Examination Timetable (2025-01 Semester) for Degree & Postgraduate Programmes_First Draft (Student)

              Dear Students, 

              Attached is the First Draft of the (2025-01 Semester) Final Examination Timetable for Degree and Postgraduate Programmes (Sarawak Campus).  Please note that this timetable is subject to change until we release the FINAL VERSION. If you notice any scheduling conflicts, please inform the Exam Centre by 24 March 2025. 

              It is important to use the latest examination timetable from IIS and avoid relying on information from other sources. Any issues caused by using an outdated version of the timetable will be solely the responsibility of the student.

              Thank you.  & Centre For Pre-U Studies - Ms. Felicia Anak Girim , feliciaag@ucsiuniversity.edu.my
            </p>
            <br>
            <a href="https://iisv2.ucsiuniversity.edu.my/apex/f?p=520:9999:2167395742647::::P9999_BFILE_ID:1011181">Download</a>
          </div>
        </li>
      </ul>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/default.jpg" alt="Image" class="image"  @click="onClickImage3()">
          <div class="text-content">
            <h3>17-March -2025 11:24am</h3>
            <p>
              Second Draft_ Final Exam Postgraduate Programme Semester 2025-01

              Dear Students,

              Attached is the SECOND DRAFT of examination timetable for Postgraduate Programme semester 2025-01

              Please check for any error/clashing and email your feedback by 20th March 2025.

              To Exam Centre at examcentre@ucsiuniversity.edu.my


              The timetable is subject to change until the final version is published. Please avoid arranging any other activities during examination period to prevent clashing.

              Please download the latest examination timetable from IIS and avoid using information from other sources.

              Any problems that occurred due to the student using an obsolete version of the examination timetable will be solely bear by the student.

              Please download the file below (2nd Draft Postgraduate Programme Semester 2025-01)

              Thank you,

              Examination Center
            </p>
            <br>
            <a href="https://iisv2.ucsiuniversity.edu.my/apex/f?p=520:9999:2167395742647::::P9999_BFILE_ID:1010725">Download</a>
          </div>
        </li>
      </ul>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/default.jpg" alt="Image" class="image"  @click="onClickImage4()">
          <div class="text-content">
            <h3>17-March -2025 11:21am</h3>
            <p>
              Second Draft_ Final Exam Foundation Programme Semester 2025-02

              Dear Students,

              Attached is the SECOND DRAFT of examination timetable for Foundation Programme semester 2025-02

              Please check for any error/clashing and email your feedback by 20th March 2025.

              To Exam Centre at examcentre@ucsiuniversity.edu.my

              The timetable is subject to change until the final version is published. Please avoid arranging any other activities during examination period to prevent clashing.

              Please download the latest examination timetable from IIS and avoid using information from other sources.

              Any problems that occurred due to the student using an obsolete version of the examination timetable will be solely bear by the student.

              Please download the file below (2nd Draft Foundation Programme Semester 2025-02)

              Thank you,

              Examination Centre
            </p>
            <br>
            <a href="https://iisv2.ucsiuniversity.edu.my/apex/f?p=520:9999:2167395742647::::P9999_BFILE_ID:1010721">Download</a>
          </div>
        </li>
      </ul>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/default.jpg" alt="Image" class="image"  @click="onClickImage5()">
          <div class="text-content">
            <h3>14-March -2025 12:26pm</h3>
            <p>
              FINAL VERSION of examination timetable for General Programmes semester (Short) 2025-02 intake February - April

              Dear Students,

              Attached is the FINAL VERSION of the examination timetable for the General Programme semester 2025-02 (Short Semester)

              Please avoid scheduling any other activities during the examination period to avoid conflicts.

              Please download the latest examination timetable from IIS and avoid using information from other sources.

              Any problems that occurred due to the student using an obsolete version of the examination timetable will be solely bear by the student.

              Please download the file below (Final Version Exam General Programme Semester 2025-02 Short)

              Thank you,

              Examination Centre
            </p>
            <br>
            <a href="https://iisv2.ucsiuniversity.edu.my/apex/f?p=520:9999:2167395742647::::P9999_BFILE_ID:1009953">Download</a>
          </div>
        </li>
      </ul>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/default.jpg" alt="Image" class="image"  @click="onClickImage6()">
          <div class="text-content">
            <h3>06-March -2025 01:52pm</h3>
            <p>
              Sarawak Campus Final Examination Timetable (2025-01 Semester) for Diploma & Foundation Programmes_Final Version (Student)
              
              Dear Students, 

              Please find attached the final version of the Final Examination Timetable for the Diploma and Foundation Programmes (Sarawak Campus). Kindly ensure you refer to the most up-to-date timetable available on IIS, and refrain from relying on information from other sources. Any issues resulting from the use of an outdated timetable will be the responsibility of the student.
            </p>
            <h4>Important Note (Self-Print Examination Slip):</h4>
            <p>Students are required to print their examination slip directly from their IIS account. For instructions on how to do this, please refer to the attached document.
            Thank you. 
            </p>
          </div>
        </li>
      </ul>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/add_drop.jpg" alt="Image" class="image"  @click="onClickImage7()">
          <div class="text-content">
            <h3>20-February -2025 04:10pm</h3>
            <p>
              REGISTRAR’S OFFICE: ADD/DROP/WITHDRAWAL COURSE PERIOD 2025-02 (Diploma & Bachelor Intake 2024-09 Onwards & Foundation)
            </p>
            <br>
            <a href="https://iisv2.ucsiuniversity.edu.my/apex/f?p=520:9999:2167395742647::::P9999_BFILE_ID:997910">Download</a>
          </div>
        </li>
      </ul>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/default.jpg" alt="Image" class="image"  @click="onClickImage8()">
          <div class="text-content">
            <h3>20-January -2025 10:15am</h3>
            <p>
              Sarawak Campus Master Class Timetable 2025-01 Semester (Final Version)
              
              Dear Students,

              Kindly find the attached Master Class Timetable for Semester 2025-01 (Sarawak Campus) -  Final Version for your reference.

              For any enquiries regarding the Master Class Timetable, please proceed to the respective Faculty Administrator :

              Faculty of Hospitality and Tourism Management - Ms. Ivy Irvine Mikal, ivyirvine@ucsiuniversity.edu.my

              Faculty of Business & Management & Centre For Pre-U Studies - Ms. Felicia Anak Girim, feliciaag@ucsiuniversity.edu.my
            </p>
            <br>
            <a href="  https://iisv2.ucsiuniversity.edu.my/apex/f?p=520:9999:2167395742647::::P9999_BFILE_ID:986058">Download</a>
          </div>
        </li>
      </ul>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="./assets/fpx.jpg" alt="Image" class="image"  @click="onClickImage9()">
          <div class="text-content">
            <h3>15-January -2025 10:04am</h3>
            <p>
              FPX Service Schedule Downtime 2025
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
    onClickImage4(){
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
    onClickImage5(){
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
    onClickImage6(){
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
    onClickImage7(){
    const imageUrl = require('./assets/add_drop.jpg')
      Swal.fire({
        imageUrl: imageUrl,
        imageWidth: 500,
        imageHeight: 300,
        imageAlt: "Custom image",
        confirmButtonText: 'OK',
        confirmButtonColor: '#FF0000', // change the OK button color to red
      });
    },
    onClickImage8(){
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
    onClickImage9(){
    const imageUrl = require('./assets/fpx.jpg')
      Swal.fire({
        imageUrl: imageUrl,
        imageWidth: 600,
        imageHeight: 400,
        imageAlt: "Custom image",
        confirmButtonText: 'OK',
        confirmButtonColor: '#FF0000', // change the OK button color to red
      });
    },
    onClickImage10(){
    const imageUrl = require('./assets/registar.jpg')
      Swal.fire({
        imageUrl: imageUrl,
        imageWidth: 500,
        imageHeight: 600,
        imageAlt: "Custom image",
        confirmButtonText: 'OK',
        confirmButtonColor: '#FF0000', // change the OK button color to red
      });
    },
    onClickImage11(){
    const imageUrl = require('./assets/registar2.jpg')
      Swal.fire({
        imageUrl: imageUrl,
        imageWidth: 500,
        imageHeight: 600,
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
  /* z-index: 1; Ensure the banner is above other content */
  object-fit: cover
}

.vueper-slide {
  position: relative;
  width: 100%;
  height: 100%;
}

.vueper-slide img {
  position: fixed;
  width: 100%;
  height: 100%;
  object-fit: cover; /* Change to contain to prevent cropping */
  object-position: center;
  max-width: 100%; /* Add max-width to prevent horizontal overflow */
  max-height: 100vh; /* Add max-height to prevent vertical overflow */
}

.announcement {
  position: relative;
  margin-top: -67vh; /* Reduce this value to move it closer */
  padding: 20px;
  z-index: 2;
  background-color: #fff; /* Ensure a solid background */
}

.title {
  display: flex;
  /* margin-bottom: 10px; */
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
