<template>
   
  <div class="header m-10">
    <h1 class="mb-4 text-4xl tracking-tight leading-none text-center md:text-5xl lg:text-6xl">
      projects
    </h1>

    <div class="grid grid-cols-1 md:grid-cols-3 p-4 mt-24 gap-8 cvp">
          <div class="max-w-sm p-6 shadow hover:shadow-xl rounded-lg">
            <img src="../assets/static/datacollection.png" alt="" />
            <div class="text-start">
              <h5 class="mt-6 text-2xl font-semibold tracking-tight text-gray-900">Collect</h5>

              <p class="mb-3 font-normal text-gray-500 mt-4">
                I have data collection and management experience with QuestionPro, Zonka,
                BeautifulSoup, Commcare and Airtable.
              </p>
            </div>
          </div>
          <div class="max-w-sm p-6 shadow hover:shadow-xl rounded-lg">
            <img src="../assets/static/natural-language-processing.png" alt="" />
            <div class="text-start">
              <h5
                class="mt-6 text-align-start mb-2 text-2xl font-semibold tracking-tight text-gray-900"
              >
                Process
              </h5>
              <p class="mt-4 font-normal text-gray-500">
                I can offer support on improving existing workflows and creation of new processes,
                covering data transformation with SQL and predictive Analysis with Machine learning.
              </p>
            </div>
          </div>
          <div class="max-w-sm p-6 shadow hover:shadow-xl rounded-lg">
            <img src="../assets/static/statistics.png" alt="" />
            <div class="text-start">
              <h5 class="mt-6 text-2xl font-semibold tracking-tight text-gray-900">Visualize</h5>

              <p class="mt-4 font-normal text-gray-500">
                I have experience creating interactive Dashboards and charts that provide vaulable
                insights with Power-Bi, Microsoft Excel and Python.
              </p>
            </div>
          </div>
        </div>

    <p class="mt-8 text-center">A sample of my work</p>
  </div>

  <div class="project flex justify-center items-center">
    <div class="grid grid-cols-2 max-md:grid-cols-1 p-8 gap-8 portfolio-container">
      <div class="box text-center text-white flex justify-center rounded-lg portfolio-item">
        <img
          class="h-auto max-w-md rounded-lg scale-100"
          src="../assets/projects/migrants.jpg"
          alt=""
        />
        <div class="box-content">
          <h3 class="title"><strong>Personal project</strong></h3>
          <a
            target="_blank"
            href="https://app.powerbi.com/view?r=eyJrIjoiYmU1NjVjNTMtODc4My00NjYyLWJjYTItZGIzM2UwOWU5ODY1IiwidCI6ImM3NmZjOWRjLTc0OTQtNDhhOC1hYzFmLTg1YTJmZTI0ZWQzZiJ9"
            class="post portfolio-lightbox"
            >Analysis on Global Dead & missing Migrants 2014-2015</a
          >
        </div>
      </div>
      <div class="box rounded-lg portfolio-item">
        <img class="h-auto max-w-md rounded-lg" src="../assets/projects/bar3.png" alt="" />
        <div class="box-content">
          <h3 class="title"><strong>Personal project</strong></h3>
          <a
            target="_blank"
            href="https://github.com/abdullah461/Analysis-on-enviromental-impact-of-food-production.git"
            class="post"
            >Analysis on enviromental impact of food production</a
          >
        </div>
      </div>
      <div class="box rounded-lg portfolio-item">
        <img class="h-auto max-w-md rounded-lg" src="../assets/projects/un.jpeg" alt="" />
        <div class="box-content">
          <h3 class="title"><strong>Personal project</strong></h3>
          <a target="_blank" href="" class="post"
            >Analysis on Unemployment in Nigeria from 2015 to 2021</a
          >
        </div>
      </div>
      <div class="box rounded-lg portfolio-item">
        <img
          class="h-auto max-w-md rounded-lg"
          src="../assets/projects/common-wealth.jpeg"
          alt=""
        />
        <div class="box-content">
          <h3 class="title"><strong>Personal project</strong></h3>
          <a target="_blank" href="https://github.com/abdullah461/Common-wealth-games.git" class="post"
            >Analysis on common wealth games 2022 medals</a
          >
        </div>
      </div>
      <div class="box rounded-lg portfolio-item">
        <img class="h-auto max-w-md rounded-lg" src="../assets/projects/sales.png" alt="" />
        <div class="box-content">
          <h3 class="title"><strong>Personal project</strong></h3>
          <a target="_blank" href="" class="post"
            >Analysis on Unemployment in Nigeria from 2015 to 2021</a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Kaushan+Script&family=Montserrat&family=Pacifico&display=swap');

/* @media (min-width: 1024px) {
  .project {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
} */
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
</style>
<script>


  /**
   * Initiate portfolio lightbox 
   */
  // const portfolioLightbox = GLightbox({
  //   selector: '.portfolio-lightbox'
  // });

</script>