<template>
    <div>
      <h1>Кого стоит качать в танках?</h1>
  <hr>
   <ul>
     <li>Совок</li>
     <li>ИС-7</li>
     <li>Ису-152(Бабаха)</li>
   </ul>
   <hr>
   <PictureComponent/>
    </div>
  </template>
  
  <script>

import PictureComponent from './PictureComponent.vue';

  export default {
    name: 'TestComponent',
    components: {
     PictureComponent
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  h3 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  }
  </style>