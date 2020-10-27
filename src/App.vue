<template>
 <div id="app">
   
   <login/>
 </div>
</template>

<script>
 import Login from './components/Login.vue';
 export default {
 name: 'app',
 components: {
 Login
 }
 };

</script>

<style>
 #app {
 font-family: 'Avenir', Helvetica, Arial, sans-serif;
 -webkit-font-smoothing: antialiased;
 -moz-osx-font-smoothing: grayscale;
 text-align: center;
 
 margin-top: 60px;
 
 }

  
  </style>