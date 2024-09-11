<template>
  <div class="announcement">
    <div class="title">
      <h1>Announcement</h1>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="../assets/announcement1.jpg" alt="Image" class="image">
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
          <img src="../assets/default.jpg" alt="Image" class="image">
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
          <img src="../assets/announcement2.jpg" alt="Image" class="image">
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
          <img src="../assets/coffee.jpg" alt="Image" class="image">
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
          <img src="../assets/honours.jpg" alt="Image" class="image">
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
          <img src="../assets/whatsnext.jpg" alt="Image" class="image">
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
          <img src="../assets/boost.jpg" alt="Image" class="image">
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
          <img src="../assets/diet.jpg" alt="Image" class="image">
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
          <img src="../assets/contact.jpg" alt="Image" class="image">
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
</template>

<script>
export default {
  name: 'AnnouncementPage',
  data() {
    return {};
  }
};
</script>

<style scoped>
.announcement {
  top: 0; /* Position it at the top of the viewport */
  left: 0; /* Position it at the left edge of the viewport */
  width: 100%; /* Take up the full width of the viewport */
  z-index: 1; /* Ensure it appears above other elements */
  display: flex; /* Stack elements vertically */
  flex-direction: column;
  margin-top: 33%;
}

.title {
  display: flex;
  justify-content: center;
  padding: 20px;
}

.paragraph-container {
  display: flex; /* Make the paragraph container a flex container */
  flex-direction: column; /* Stack elements vertically within the container */
  padding: 20px;
}

ul {
  list-style-type: none; /* Remove bullet points */
  padding: 0; /* Remove default padding */
}

li {
  margin-bottom: 20px; /* Add some space between list items */
  display: flex; /* Use flexbox for layout */
  align-items: flex-start; /* Align items at the top */
}

.image {
  max-width: 50px; /* Ensure the image doesn't exceed the width of the container */
  max-height: 50px; /* Ensure the image doesn't exceed the height of the container */
  margin-right: 20px; /* Add margin between the image and text */
  /* border-radius: 50%; Make the image circular (optional) */
}

.text-content {
  display: flex;
  flex-direction: column;
  align-items: flex-start; /* Align text to the left */
}

h3 {
  margin: 0; /* Remove default margin of <h3> */
  text-align: left; /* Ensure the heading text is left-aligned */
  margin-bottom: 20;
}

p {
  margin: 0; /* Remove default margin of <p> */
  text-align: justify; /* Justify the paragraph text */
}
</style>

