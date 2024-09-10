<template>
  <div class="announcement">
    <div class="title">
      <h1>Announcement</h1>
    </div>
    <div class="paragraph-container">
      <ul>
        <li>
          <img src="../assets/logo.png" alt="Image" class="image">
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
          <img src="../assets/logo.png" alt="Image" class="image">
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
          <img src="../assets/logo.png" alt="Image" class="image">
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
  border-radius: 50%; /* Make the image circular (optional) */
}

.text-content {
  display: flex;
  flex-direction: column;
  align-items: flex-start; /* Align text to the left */
}

h3 {
  margin: 0; /* Remove default margin of <h3> */
  text-align: left; /* Ensure the heading text is left-aligned */
}

p {
  margin: 0; /* Remove default margin of <p> */
  text-align: justify; /* Justify the paragraph text */
}
</style>

