<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>


  <header>
    <nav class="bg-white dark:bg-gray-900 w-full z-20 top-0 left-0">
  <div class="max-w-screen-xl flex justify-between items-center justify-center mx-auto p-2" id="na">
    <RouterLink to="/" class="">

        <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white sm:hidden" id="ull"><img src="../src/assets/static/lg.png" alt=""></span>
        <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white " id="full"><img src="../src/assets/static/aalogo-removebg-preview.png" alt=""></span>
      </RouterLink>
  <div class="items-center justify-between  w-full md:flex md:w-auto md:order-1" id="">
    
    <ul class="flex justify-end py-4   font-medium border border-gray-100 rounded-lg  md:flex-row md:space-x-8 md:mt-0 md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700">
     
        <RouterLink to="/about">about me</RouterLink>
       
    </ul>
  </div>
  </div>
</nav>
    <div class="wrapper">
      <!-- <HelloWorld msg="You did it!" /> -->
    </div>
  </header>
  <RouterView />
  <footer class="flex justify-center">
    <ul class="flex gap-4 justify-center">
    
      <li><a target="_blank" href="https://www.linkedin.com/in/abdullah-abubakar-5a7965197"><img src="../src/assets/static/linkedin.png" alt="linkedin"></a></li>
      <li><a target="_blank" href="https://github.com/abdullah461"><img src="../src/assets/static/github.png" alt="github"></a></li>
      <li><a target="_blank" href="https://twitter.com/Abu_______bakar"><img src="../src/assets/static/twitter.png" alt="twitter"></a></li>
      <li><a target="_blank" href="https://www.instagram.com/abdvvl"><img src="../src/assets/static/instagram.png" alt="instagram"></a></li>
      <li><a target="_blank" href="https://www.kaggle.com/abdullahabubakar"><img src="../src/assets/static/kaggle.png" alt="kaggle"></a></li>
    </ul>
  </footer>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Kaushan+Script&family=Pacifico&display=swap');

/* font-family: 'Dancing Script', cursive;
font-family: 'Kaushan Script', cursive;
font-family: 'Pacifico', cursive; */
@import url('https://fonts.googleapis.com/css2?family=Libre+Bodoni:wght@400;500&display=swap');

 @import url('https://fonts.cdnfonts.com/css/zian');

                
*,:after,:before{
  border: none;
}
header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
 
}
header{
  font-family: 'Libre Bodoni', serif;
}
nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  font-family: 'Zian', sans-serif;
  display: inline-block;
  padding: 0 1rem;
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    /* text-align: left;
    margin-left: -1rem; */
    font-size: 1rem;
    padding: 1rem 0;
    margin-top: 0.5rem;
  }
}
@media (min-width: 375px) {
ul {
  justify-content: end;
}}
@media (min-width: 500px){
  	#ull{
      display: none;
    }
}
@media (max-width: 500px) {
  #full{
  display: none;
}
}
</style>
