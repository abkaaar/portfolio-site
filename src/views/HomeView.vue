<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <main>
    <section class="mt-10 sm:mt-0 bg-white sm:flex justify-between">
      <div
        class="flex flex-col items-start py-4 px-4 mx-auto max-w-screen-xl text-center lg:py-16 lg:px-12"
        mt-0
      >
        <p class="mb-8 text-lg font-normal text-gray-500">👋 I'am a</p>
        <h1
          class="mb-4 text-start text-xl font-medium tracking-tight leading-none md:text-2xl lg:text-4xl"
        >
          software developer
        </h1>
        <p class="text-start mb-8 text-lg font-normal text-gray-500">
          I have experience in designing and building modern digital products at scale and a strong
          track record of leveraging technologies to help teams and clients achieve their goals.
        </p>
        <div
          class="flex justify-center gap-5 mb-8 lg:mb-16 sm:flex-row sm:justify-center sm:space-y-0 sm:space-x-4"
        >
          <a
            target="_blank"
            href="mailto: AbdullahAbubakar461@gmail.com"
            class="r inline-flex gap-2 justify-center items-center py-3 px-5 text-base font-medium text-center text-black rounded-lg bg-gray-100 hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 focus:ring-primary-900"
          >
            Contact
          </a>
          <RouterLink
            to="/web-development"
            class="r inline-flex gap-2 justify-center items-center py-3 px-5 text-base font-medium text-center text-gray-900 rounded-lg border border-gray-300 focus:ring-4 focus:ring-gray-100"
          >
            Projects</RouterLink
          >
        </div>
        <!-- <div class="cert w-full flex justify-center sm:justify-start  mb-8">
          <div class="flex gap-2">
            <img src="../assets/static/icon/mckinsey.png"   alt="" class="w-[70px] h-[70px]"/>
            <img src="../assets/static/icon/data-analysis-using-python.png" alt="" class="w-[70px] h-[70px]"/>
            <img src="../assets/static/icon/introduction-to-data-science.png" alt="" class="w-[70px] h-[70px]"/>
          </div>
        </div> -->
      </div>
      <div class="flex justify-center items-center">
        <img
          src="https://ik.imagekit.io/to6pf1whv/web%20design%20in%20abuja/web-design-expert-in-abuja-abdull.jpg?updatedAt=1716039997898"
          alt="Abubakar Abdullahi"
          class="border-4 rounded-md"
        />
      </div>
      <div class="sm:hidden text-center mb-8"><p>Lets connect below 🤝</p></div>
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
  width: 70%;
  height: auto;
}
</style>
