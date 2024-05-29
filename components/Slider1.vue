<template>
    <div class="relative ">
      <video autoplay muted class="w-full h-1/2 filter brightness-[30%]">
        <source src="/asset/images/f1intro.mp4" type="video/mp4">
      </video>
    </div>
    <div class="flex items-end absolute inset-y-0 px-4 ">
                <div class="my-2 items-center text-white border-white max-w-max mx-auto rounded gap-6 px-2">
                    <br>
                    <hi class="font-bold text-3xl mb-16">WELCOME TO FORMULA 1 GURU</hi>
                    <br>
                <p>Predict Podiums in Sprints and Races, and score points for each correct prediction.</p> 
                <P> Create leagues with your friends and colleagues or join other leagues and win amazing prizes including</P>
                <P>a Paddock Experience with Formula 1 Guru where you will be hosted by Scuderia Ferrari</p>
                    <br>
                <NuxtLink to="/about" class="bg-red-700 hover:bg-red-500 font-bold py-2 px-4 rounded text-white">Play Now</NuxtLink>
                <img src="/asset/images/ferrari.png" class="w-[100px] h-[120px] mt-4">
                </div>
            </div>
  </template>
  
  <script>
  export default {
    name: 'VideoComponent'
  }
  </script>
  
  <style scoped>
  video {
    max-width: 100%;
    height: auto;
  }
  </style>
  