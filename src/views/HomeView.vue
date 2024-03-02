<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <main>
    <section class="bg-white">
      <div class="py-4 px-4 mx-auto max-w-screen-xl text-center lg:py-16 lg:px-12" mt-0>
        <p class="mb-8 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 xl:px-48">
          Hey! I'am a
        </p>
        <h1
          class="mb-4 text-4xl font-extrabold tracking-tight leading-none md:text-5xl lg:text-6xl"
        >
          software developer
        </h1>
        <p class="mb-8 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 xl:px-48">
          I've experience in designing & building mordern digital products at scale and strong
          track record in leveraging technologies to help teams and clients achieve their goals. <br>
          Also an aspiring data scientist with fervor for exploring & transforming raw data into valuable insights.
        </p>
        <div
          class="flex justify-center gap-5 mb-8 lg:mb-16 sm:flex-row sm:justify-center sm:space-y-0 sm:space-x-4"
        >
          <a
            target="_blank"
            href="mailto: AbdullahAbubakar461@gmail.com"
            class="r inline-flex gap-2 justify-center items-center py-3 px-5 text-base font-medium text-center text-black rounded-lg bg-gray-100 hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 focus:ring-primary-900"
          >
            Contact me
          </a>
          <RouterLink
            to="/writings"
            class="r inline-flex gap-2 justify-center items-center py-3 px-5 text-base font-medium text-center text-gray-900 rounded-lg border border-gray-300 focus:ring-4 focus:ring-gray-100"
          >
            Writings</RouterLink
          >
        </div>
        <!-- <div class="px-4 mx-auto text-center md:max-w-screen-md lg:max-w-screen-lg lg:px-36">
          <span class="font-sem uppercase">TOOLS</span>
        </div> -->
        <div class="flex p-4">
          <RouterLink
            to="/project"
            class="r w-full inline-flex gap-2 justify-center items-center py-3 px-5 text-base font-medium text-center text-gray-900 rounded-lg border border-gray-300 focus:ring-4 focus:ring-gray-100"
          >
            Data science projects</RouterLink
          >
        </div>

      
      </div>
    </section>
  </main>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Kaushan+Script&family=Montserrat&family=Pacifico&display=swap');
/* font-family: 'Dancing Script', cursive;
font-family: 'Kaushan Script', cursive;
font-family: 'Pacifico', cursive; */
main {
  font-family: 'Montserrat', sans-serif;
}
main h1 {
  font-family: 'Zian', sans-serif;
  color: black;
}
.r:hover {
  color: white;
  background-color: black;
}
img {
  width: 50%;
  height: auto;
}
</style>
