<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div class="header mt-10">
    <h1 class="mb-4 text-4xl tracking-tight leading-none text-center">projects</h1>
    <div class="flex justify-center gap-4">
      <RouterLink to="/web-development" class="underline"> Web Development </RouterLink>
      <span> | </span><RouterLink to="/data-science" class="underline"> Data Science </RouterLink>
    </div>
    <p class="mt-8 text-center">A sample of my web projects</p>
    <div class="stacks mt-10 mb-10">
      <div class="items">
        <img src="../assets/static/stacks/express-js-48.png" alt="" />
        <img src="../assets/static/stacks/java-48.png" alt="" />
        <img src="../assets/static/stacks/javascript-48.png" alt="" />
        <img src="../assets/static/stacks/nextjs-48.png" alt="" />
        <img src="../assets/static/stacks/react-native-48.png" alt="" />
      </div>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-3 p-4 mt-24 mb-24 gap-8 cvp">
      <!-- items -->
      <div
        class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
      >
        <img class="rounded-t-lg w-full" src="../assets/projects/formlr.jpeg" alt="" />
        <div class="p-5">
          <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
            Formlr</h5>

          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
            Formlr is a survey creation tool that lets users create and analyze surveys, built with Nextjs.
          </p>
          <a
            href="https://formlr.onrender.com"
            class="inline-flex items-center px-6 py-2 text-sm font-medium text-center text-white bg-black rounded-lg hover:bg-black-100 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
          >
            visit
          </a>
        </div>
      </div>
      <div
        class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
      >
        <img class="rounded-t-lg w-full" src="../assets/projects/codelrcover1.png" alt="" />
        <div class="p-5">
          <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
            Codelr community</h5>

          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
          A beautiful Website design for Codelr - a tech drivien community
          </p>
          <a
            href="https://codelr-website.onrender.com"
            class="inline-flex items-center px-6 py-2 text-sm font-medium text-center text-white bg-black rounded-lg hover:bg-black-100 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
          >
            visit
          </a>
        </div>
      </div>
      <div
        class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
      >
        <img class="rounded-t-lg w-full" src="../assets/projects/scholardex.jpeg" alt="" />
        <div class="p-5">
          <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
            scholardex</h5>

          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
            A scholarship management system to manage scholarships, applications, review and processes. built with Nextjs, react, Postgres db, prisma, Neon dbms, Authjs
          </p>
          <a
            href="https://scholardex.vercel.app"
            class="inline-flex items-center px-6 py-2 text-sm font-medium text-center text-white bg-black rounded-lg hover:bg-black-100 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
          >
            visit
          </a>
        </div>
      </div>
      <div
        class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
      >
        <img class="rounded-t-lg w-full" src="../assets/projects/auth-pic.png" alt="" />
        <div class="p-5">
          <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
            Auth system
          </h5>

          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
            An advanced authentication and authorization system built using react, nextjs, Authjs, shadcn-UI, prisma and Neon-DB
          </p>
          <a
            href="https://auth-system-kappa.vercel.app"
            class="inline-flex items-center px-6 py-2 text-sm font-medium text-center text-white bg-black rounded-lg hover:bg-black-100 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
          >
            visit
          </a>
        </div>
      </div>
      <div
        class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
      >
        <img class="rounded-t-lg w-full" src="https://ik.imagekit.io/to6pf1whv/web%20design%20in%20abuja/works/ozone.png?updatedAt=1717106770531" alt="ozone.co" />
        <div class="p-5">
          <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
            myozone.co
          </h5>

          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
            This is a website for a climate tech company focusing on cng financing in Nigeria.
          </p>
          <a
            href="https://myozone.co"
            class="inline-flex items-center px-6 py-2 text-sm font-medium text-center text-white bg-black rounded-lg hover:bg-black-100 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
          >
            visit
          </a>
        </div>
      </div>
      <div
        class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
      >
        <img class="rounded-t-lg w-full" src="https://ik.imagekit.io/to6pf1whv/web%20design%20in%20abuja/works/ats.png?updatedAt=1717106770071" alt="Abuja tech summit" />
        <div class="p-5">
          <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
            Abuja tech summit
          </h5>

          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
            Website for Abuja tech summit event. 
          </p>
          <a
            href="https://abujatechsummit.com.ng"
            class="inline-flex items-center px-6 py-2 text-sm font-medium text-center text-white bg-black rounded-lg hover:bg-black-100 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
          >
            visit
          </a>
        </div>
      </div>
      <div
        class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
      >
        <img class="rounded-t-lg w-full" src="https://ik.imagekit.io/to6pf1whv/web%20design%20in%20abuja/pandacare.png?updatedAt=1717105621349" alt="pandacare" />
        <div class="p-5">
          <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
            PandacareNg
          </h5>

          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
            Website for a health agency providing various health services.
          </p>
          <a
            href="https://www.pandacareng.com"
            class="inline-flex items-center px-6 py-2 text-sm font-medium text-center text-white bg-black rounded-lg hover:bg-black-100 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
          >
            visit
          </a>
        </div>
      </div>
   

         </div>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Kaushan+Script&family=Montserrat&family=Pacifico&display=swap');

.header h1 {
  color: black;
}
.post:hover {
  text-decoration: underline;
}
.box {
  color: #fff;
  background: linear-gradient(to right, #5988ff, #5988ff);
  font-family: 'Montserrat', sans-serif;
  text-align: center;
  position: relative;
  z-index: 1;
}
.box:before {
  content: '';
  height: 40px;
  width: 40px;
  border-top: 1px solid #fff;
  border-right: 1px solid #fff;
  opacity: 0;
  transform: scale(0);
  transform-origin: top right;
  position: absolute;
  top: 20px;
  right: 20px;
  transition: all 0.4s ease;
  z-index: 1;
}
.box:hover:before {
  opacity: 1;
  transform: scale(1);
}
.box img {
  width: 100%;
  height: 100%;
  background-size: cover;
  background-position: center;
  transition: all 0.4s ease 0s;
}
.box:hover img {
  opacity: 0.2;
}
.box-content {
  width: 100%;
  opacity: 0;
  transform: translateX(-50%) translateY(-50%);
  position: absolute;
  top: 50%;
  left: 50%;
  z-index: 2;
  transition: all 0.4s ease;
}
.box:hover .box-content {
  opacity: 1;
}
.box .icon {
  padding: 0;
  margin: 0;
  list-style: none;
  opacity: 0;
  position: absolute;
  bottom: 10px;
  left: 20px;
  z-index: 2;
  transition: all 0.4s ease;
}
.box:hover .icon {
  opacity: 1;
}
.box .icon li {
  margin: 0 3px;
  display: inline-block;
}
.box .icon li a {
  color: #fff;
  font-size: 15px;
  text-align: center;
  line-height: 32px;
  height: 35px;
  width: 35px;
  border: 2px solid #fff;
  box-shadow: 1px 1px 2px rgba(0, 0, 0, 0.6);
  display: block;
  transition: all 0.3s ease-in-out;
}
.box .icon li a:hover {
  color: #ff6600;
  background: #fff;
  transform: rotate(360deg);
  border-radius: 50px;
}

/* stacks */
.stacks {
  width: 100%;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
}
.stacks h2 {
  font-size: 26px;
  color: #000060;
  font-weight: 800;
  margin-bottom: 1em;
}
.stacks .items {
  display: flex;
  gap: 1.2em;
  width: 60%;
  align-items: center;
  justify-content: space-evenly;
  flex-wrap: wrap;
}
.stacks .items img {
  width: 50px;
  height: auto;
  opacity: 0.5;
  transition: 0.3s;
  cursor: pointer;
}
.stacks .items img:hover {
  opacity: unset;
}
</style>
