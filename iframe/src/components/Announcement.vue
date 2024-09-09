<template>
    <div class="announcement">
      <div class="title">
        <h1>Announcement</h1>
      </div>
      <div class="paragraph-container">
        <!-- <img src="../assets/logo.png" alt="Image" class="image"> -->
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean elit eros, tincidunt et magna et, tincidunt mattis nulla. Sed sed metus egestas, egestas purus vel, pretium lacus. Vivamus id sem nunc. Nam in cursus dui. Vivamus finibus quam at nisi semper pharetra. Sed neque leo, vulputate eu finibus at, rhoncus eget ex. Praesent id tellus sit amet ex malesuada commodo. Fusce fermentum, nisi sit amet dictum iaculis, urna dolor vestibulum augue, id posuere erat ex eget arcu. Donec eu orci tincidunt, malesuada enim malesuada, porttitor leo. Integer varius congue quam sed condimentum. Quisque tristique, eros at commodo vehicula, sem dui tincidunt ex, nec mollis dui risus ac dui. Ut ac commodo neque. Etiam ornare a ante vitae sagittis. Sed scelerisque pretium odio et ornare.</p>
      </div>
      <div class="paragraph-container">
        <!-- <img src="../assets/logo.png" alt="Image" class="image"> -->
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean elit eros, tincidunt et magna et, tincidunt mattis nulla. Sed sed metus egestas, egestas purus vel, pretium lacus. Vivamus id sem nunc. Nam in cursus dui. Vivamus finibus quam at nisi semper pharetra. Sed neque leo, vulputate eu finibus at, rhoncus eget ex. Praesent id tellus sit amet ex malesuada commodo. Fusce fermentum, nisi sit amet dictum iaculis, urna dolor vestibulum augue, id posuere erat ex eget arcu. Donec eu orci tincidunt, malesuada enim malesuada, porttitor leo. Integer varius congue quam sed condimentum. Quisque tristique, eros at commodo vehicula, sem dui tincidunt ex, nec mollis dui risus ac dui. Ut ac commodo neque. Etiam ornare a ante vitae sagittis. Sed scelerisque pretium odio et ornare.</p>
      </div>
      <div class="paragraph-container">
        <!-- <img src="../assets/logo.png" alt="Image" class="image"> -->
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean elit eros, tincidunt et magna et, tincidunt mattis nulla. Sed sed metus egestas, egestas purus vel, pretium lacus. Vivamus id sem nunc. Nam in cursus dui. Vivamus finibus quam at nisi semper pharetra. Sed neque leo, vulputate eu finibus at, rhoncus eget ex. Praesent id tellus sit amet ex malesuada commodo. Fusce fermentum, nisi sit amet dictum iaculis, urna dolor vestibulum augue, id posuere erat ex eget arcu. Donec eu orci tincidunt, malesuada enim malesuada, porttitor leo. Integer varius congue quam sed condimentum. Quisque tristique, eros at commodo vehicula, sem dui tincidunt ex, nec mollis dui risus ac dui. Ut ac commodo neque. Etiam ornare a ante vitae sagittis. Sed scelerisque pretium odio et ornare.</p>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'AnnouncementPage',
    data() {
      return {
          
      };
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
    flex-wrap: wrap; /* Allow elements to wrap to the next line */
    padding: 20px;
    align-items: center; /* Center the image and text vertically */
  }
  
  .image {
    max-width: 5%; /* Ensure the image doesn't exceed the width of the paragraph */
    max-height: 5%; /* Ensure the image doesn't exceed the height of the paragraph */
    margin-right: 20px; /* Add margin between the image and text */
    border-radius: 50%; /* Make the image a circle (optional) */
  }
  
  p {
    margin: 0; /* Remove default margin of <p> */
  }
  </style>