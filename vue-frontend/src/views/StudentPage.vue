<template>
    <div class="Student">
      <Student/>
    </div>
</template>
  
  
  <script>
  import Student from './components/Student.vue';

  
  
  export default {
    name: 'App',
    components: {
      Student

    }
  }
  </script>
  
  <style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
  </style>
  