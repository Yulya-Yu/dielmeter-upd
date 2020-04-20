<template>
      <div id="app">
          <div class="logo">
              <router-link to="/"><h3>Yushkov's Di-El Meter</h3></router-link>
          </div>
        <div id="nav">
          <router-link to="/">home</router-link>
          <a href="/">dielmeter</a>
          <a href="/">opportunities</a>
          <a href="/">creator</a>
          <a href="/">help</a>
          <a href="/">contact</a>
          <router-link to="/about">about</router-link>
          <router-link to="/ru">RU</router-link>
        </div>
      </div>
</template>

<script>

   export default {
      name:'Nav',
    }

 </script>
 <style scoped>
 #app {
     width: 100%;
     position: fixed;
     height: 10vh;
     display: flex;
     flex-direction: row;
     justify-content: space-around;
     line-height: 10vh;
     text-align: center;
     border-bottom: 1px solid #7b1fa2;
     font-size: 1.1rem;
     color: #333;
     background-color: #fff;
 }

 #nav {
     display: flex;
     justify-content: flex-end;
 }

 #nav a {
     text-decoration: none;
     margin-left: 2rem;
     transition: 0.2s;
 }

 #nav a:hover {
 font-size: 1.2rem;
 color: #7b1fa2;
 font-weight: 600;
 }

a {
     text-decoration: none;
     color: #333;
 }

 </style>