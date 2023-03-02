<template>
    <li class="card">
      <img :src="src" alt="">
      <h3 class="card__title">{{ series }}</h3>
    </li>
  </template>
  
  <script>
    export default {
      props: {
        series: String,
        src: String,
      }
    }
  
    // function somma(a,b) {
    //   return a + b
    // }
  
    // somma(5,10)
  </script>
  
  <style scoped>

  
  .card{
    background-color: antiquewhite;
    padding: 20px;
    border: 2px solid red;
  }
  
  </style>