<template>
    <div>
        <section class="pr-28 text-gray-400">
       
        <h1 class="  mt-24 md:px-16 xl:px-72 lg:px-48 text-6xl py-12 md:text-[Bren] lg:text-[9rem]">Crafting
          <span
            class="bg-gradient-to-r from-gray-200 to-violet-900 bg-clip-text font-extrabold tracking-wide text-transparent"
          >
            digital
          </span> experience that help 
          <span
            class="bg-gradient-to-r from-violet-900 to-gray-200 bg-clip-text font-extrabold tracking-wide text-transparent">
            people
          </span>
          </h1>
      </section>

      <section
        class=  "bg-blue bg-[linear-gradient(to_right,#4f4f4f2e_1px,transparent_1px),linear-gradient(to_bottom,#8080800a_1px,transparent_1px)] bg-[size:14px_24px] py-12"
    >
      <h2
        class="pb-6 text-center text-4xl text-orange-300 md:text-5xl lg:text-6xl"
      >
        About Me
      </h2>
      <p class="px-5 text-lg text-gray-400 md:px-24 md:text-xl lg:px-48 lg:text-2xl xl:px-96 text-justify">Experienced <span class="font-extrabold text-violet-400">front-end developer</span> 
        with a solid background in health-tech, proficient in VueJS,
         HTML5, CSS3, JavaScript (ES6+), and modern front-end tools like Tailwind CSS and Webpack. 
         Skilled in creating responsive, user-friendly, and accessible web applications. 
         Passionate about UI/UX design, performance optimization, and building secure, 
         scalable solutions that enhance the user experience, especially in healthcare technology.
        
      
        
      </p>
      </section>
      <section class="px-5 pb-12">
        <h2 class="px-5 py-12 text-4xl text-orange-300 md:text-5xl lg:px-24 lg:text-6xl xl:px-36 text-center">My Work

        </h2>
      <div class="grid grid-cols-1 gap-4 lg:grid-cols-2 xl:grid-cols-3">
        <div
          v-for="i in 3"
          :key="i"
          class="flex items-center justify-center bg-white/5 p-3 duration-500 hover:bg-white/10 rounded-lg border-2 border-violet-900"
        >
        <img src="/assets/img/Logo.jpg" class="w-24 rounded-lg" alt="Haqi Logo" />
        <div class="pl-6">
            <h3 class="pb-4 text-3xl text-orange-300">
              Haqi Channel
            </h3>
            <p class="text-gray-400">
              I share my knowledge and experience in front-end development and
              architecture through videos on my
              <a
                class="text-blue-500 underline"
                target="_blank"
                href="https://www.youtube.com/@haqi8045"
              >
                YouTube channel</a
              >.
            </p>
            <button
              role="link"
              class="pt-2 text-lg text-blue-300 underline decoration-wavy underline-offset-4 transition-colors duration-300 hover:text-blue-500"
            >
              More Info
            </button>
            </div>
        </div>


      </div>




      </section>
      <section class="px-5 pb-12">
        <h2
        class="py-12 text-4xl text-orange-300 md:text-5xl lg:px-24 lg:text-6xl xl:px-36 text-center"
      >
        Technical skills
      </h2>
      <div class="grid grid-cols-1 gap-4 lg:grid-cols-2 xl:grid-cols-3">
        <div
          class="rounded-lg border-2  border-violet-900 p-2 px-6"
        >
        <div class="flex h-fit flex-row pb-6">
          <img
             class="w-8"
             src="/assets/img/programming-monitor-svgrepo-com.svg"
             alt="Programming monitor icon"
          >
          <h3
              class="text-balance pl-6 text-xl font-extrabold text-orange-300"
            >
              Languages and Frameworks
            </h3>
        </div>
        <div class="flex flex-row flex-wrap justify-around">
            <div class="flex flex-col items-center px-3 text-white">
              <img
                class="w-12"
                src="/assets/img/vue-vuejs-javascript-js-framework-svgrepo-com.svg"
                alt="vue js"
              />
              <span>VueJs</span>
            </div>
          
            <div class="flex flex-col items-center px-3 text-white">
              <img
                class="w-12"
                src="/assets/img/nuxt-svgrepo-com.svg"
                alt="Nuxt"
              />
              <span>Nuxt</span>
            </div>
            <div class="flex flex-col items-center px-3 text-white">
              <img
                class="w-12"
                src="/assets/img/nodejs-icon-logo-svgrepo-com.svg"
                alt="NodeJs"
              />
              <span>NodeJs</span>
              </div>
            </div>
        </div>
        <div
          class="rounded-lg border-2  border-violet-900 p-2 px-6"
        >
        <div class="flex h-fit flex-row pb-6">
          <img
             class="w-8"
             src="/assets/img/database-svgrepo-com.svg"
             alt="Programming monitor icon"
          >
          <h3
              class="text-balance pl-6 text-xl font-extrabold text-orange-300"
            >
              Database and Analytics
            </h3>
            </div>
            <div class="flex flex-row flex-wrap justify-around">
            <div class="flex flex-col items-center px-3 text-white">
              <img
                class="w-12"
                src="/assets/img/mysql-svgrepo-com.svg"
                alt="Mysql"
              />
              <span>Mysql</span>
            </div>
            
            <div class="flex flex-col items-center px-3 text-white">
              <img
                class="w-12"
                src="/assets/img/mongodb-svgrepo-com.svg"
                alt="MongoDb"
              />
              <span>MongoDb</span>
            
            </div>
            <div class="flex flex-col items-center px-3 text-white">
              <img
                class="w-12"
                src="/assets/img/postgresql-svgrepo-com.svg"
                alt="Postgresql"
              />
              <span>Postgresql</span>
            </div>
            </div>
            </div>
            <div
            class="rounded-lg border-2  border-violet-900 p-2 px-6"
        >
        <div class="flex h-fit flex-row pb-6">
          <img
             class="w-8 bg-white rounded-lg"
             src="/assets/img/devops-svgrepo-com.svg"
             alt="Devops"
          >
          <h3
              class="text-balance pl-6 text-xl font-extrabold text-orange-300"
            >
              Devops
            </h3>
            </div>
            <div class="flex flex-row flex-wrap justify-around">
            <div class="flex flex-col items-center px-3 text-white">
              <img
                class="w-12"
                src="/assets/img/docker-svgrepo-com.svg"
                alt="Docker"
              />
              <span>Docker</span>
            </div>
            </div>
            
            
            
            
            
      </div>
        </div>
        

      </section>
      <section class="bg-[#000000] bg-[radial-gradient(#ffffff33_1px,#00091d_1px)] bg-[size:20px_20px] px-5 pb-12 lg:px-8 xl:px-12">
  <h2 class="py-12 text-4xl text-orange-300 md:text-5xl lg:px-24 lg:text-6xl xl:px-36 text-center">
    Movies that inspired me
  </h2>
  <div class="grid gap-4 px-5 lg:grid-cols-2 xl:grid-cols-4">
    
    <img src="/assets/img/socialnetwork.jpg" alt="The Social Network" class="w-full h-64 object-cover rounded-lg"/>
    <div class="pl-8">
      <h3 class="text-3xl text-orange-300">The Social Network (2010)</h3>
      <p class="pt-4 px-8 text-gray-500">Directed by David Fincher.</p>
      <p class="pt-4 text-gray-200">
        This film chronicles the founding of Facebook by Mark Zuckerberg and explores the legal and ethical challenges he faces while building one of the biggest tech companies in the world.
      </p>
    </div>

   
    
    <img src="/assets/img/happiness.jpg" alt="The Pursuit of Happyness" class="w-full h-64 object-cover rounded-lg" />
    <div class="pl-8">
      <h3 class="text-3xl text-orange-300">The Pursuit of Happyness (2006)</h3>
      <p class="pt-4 px-8 text-gray-500">Directed by Gabriele Muccino.</p>
      <p class="pt-4 text-gray-200">
        This movie follows Chris Gardner’s journey from homelessness to becoming a successful stockbroker, showcasing resilience and perseverance.
      </p>
    </div>

    
    <img src="/assets/img/moneyball.jpg" alt="Moneyball" class="w-full h-64 object-cover rounded-lg" />
    <div class="pl-8">
      <h3 class="text-3xl text-orange-300">Moneyball (2011)</h3>
      <p class="pt-4 px-8 text-gray-500">Directed by Bennett Miller.</p>
      <p class="pt-4 text-gray-200">
        This film tells the story of how Oakland A's general manager used data analytics to build a competitive baseball team, showcasing innovation and strategic thinking.
      </p>
    </div>

    <img src="/assets/img/thefounder.jpg" alt="TheFounder" class="w-full h-64 object-cover rounded-lg" />
    <div class="pl-8">
      <h3 class="text-3xl text-orange-300">The Founder (2016)
      </h3>
      <p class="pt-4 px-8 text-gray-500">Directed by John Lee Hancock</p>
      <p class="pt-4 text-gray-200">
        It depicts Ray Kroc’s acquisition and expansion of McDonald's, showing lessons on scaling a business and the complexities of partnerships.
      </p>
    </div>
  </div>
</section>
<section
class="pb-12"
>
<h2
        class="px-5 py-12 text-center text-4xl text-yellow-100 md:text-5xl lg:px-24 lg:text-6xl xl:px-36"
      >
        Links
      </h2>
      <div
        class="mx-auto grid w-fit justify-center gap-x-24 gap-y-8 px-5 md:grid-cols-2 lg:grid-cols-3"
      >
        <a target="_blank" href="https://www.youtube.com/@haqi8045"
          ><img
            class="h-14 w-48"
            src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"
            alt="YouTube logo"
        /></a>
        <a target="_blank" href="https://www.linkedin.com/in/muhammad-baihaqi-453375289/"
          ><img
            class="h-14 w-48"
            src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"
            alt="LinkedIn logo"
        /></a>
        <a target="_blank" href="https://github.com/Haqi25"
          ><img
            class="h-14 w-48"
            src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"
            alt="GitHub logo"
        /></a>
        </div>

</section>

    </div>
     </template>
 
 <script setup lang="ts">
definePageMeta({
  layout: "home",
});
</script>