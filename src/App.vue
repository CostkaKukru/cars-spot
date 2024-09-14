<script setup>

import { VueperSlides, VueperSlide } from 'vueperslides';
import 'vueperslides/dist/vueperslides.css';

import image1 from './assets/gallery/image 1.png';
import image2 from './assets/gallery/image 2.png';
import image3 from './assets/gallery/image 3.png'

const slides = [
  {
    title: 'El Teide Volcano, Spain',
    content: 'Photo by Max Rive',
    image: image1,
  },
  {
    title: 'Slide 2',
    content: 'Content for Slide 2',
    image: image2,
  },
  {
    title: 'Slide 3',
    content: 'Content for Slide 3',
    image: image3,
  },
  {
    title: 'Slide 4',
    content: 'Content for Slide 5',
    image: image1,
  },
  {
    title: 'Slide 5',
    content: 'Content for Slide 5',
    image: image2,
  },
  {
    title: 'Slide 6',
    content: 'Content for Slide 6',
    image: image2,
  },
  {
    title: 'Slide 7',
    content: 'Content for Slide 7',
    image: image2,
  },
];



</script>

<template>
  <header>
    <nav class="bg-white border-gray-200 px-4 lg:px-6 py-2.5 dark:bg-gray-800">
      <div class="flex flex-wrap justify-between items-center mx-auto max-w-screen-xl">
        <a href="https://carsspot.com" class="flex items-center">
          <img src="./assets/Group 255.png" class="mr-3" alt="CarsSpot Logo" />
        </a>
          <div class="flex items-center lg:order-2">
            <a href="#" class="text-white bg-primary-700 hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 font-medium rounded-lg text-sm px-4 lg:px-5 py-2 lg:py-2.5 mr-2 dark:bg-primary-600 dark:hover:bg-primary-700 focus:outline-none dark:focus:ring-primary-800">Zadzwoń do nas</a>
          </div>
            <div class="hidden justify-between items-center w-full lg:flex lg:w-auto lg:order-1" id="mobile-menu-2">
                <ul class="flex flex-col mt-4 font-medium lg:flex-row lg:space-x-8 lg:mt-0">
                    <li>
                        <a href="#" class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 lg:hover:bg-transparent lg:border-0 lg:hover:text-primary-700 lg:p-0">Galeria zdjęć</a>
                    </li>
                    <li>
                        <a href="#" class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 lg:hover:bg-transparent lg:border-0 lg:hover:text-primary-700 lg:p-0">FaQ</a>
                    </li>
                </ul>
        </div>
      </div>
    </nav>
  </header>

  <section>
    <div class="grid max-w-screen-xl px-4 py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-16 lg:grid-cols-12">
        <div class="mr-auto place-self-center lg:col-span-6">
            <h1 class="max-w-2xl mb-4 text-4xl font-extrabold tracking-tight leading-none md:text-5xl xl:text-6xl">Sprzedajemy samochody<br>z Europy</h1>
            <p class="max-w-2xl mb-6 font-light text-neutral-800 lg:mb-8 md:text-lg lg:text-xl">Kup komfortowy pojazd, aby każda podróż<br> była wyjątkowym przeżyciem.</p>
            <a href="#" class="inline-flex items-center justify-center px-5 py-3 mr-3 text-base font-medium text-center text-white rounded-lg bg-primary-700 hover:bg-primary-800 focus:ring-4 focus:ring-primary-300">
                Zobacz zdjęcia
                <svg class="w-5 h-5 ml-2 -mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
            </a>
            <a href="#" class="inline-flex items-center justify-center px-5 py-3 text-base font-medium text-center text-gray-900 border border-gray-300 rounded-lg hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:text-white dark:border-gray-700 dark:hover:bg-gray-700 dark:focus:ring-gray-800">
                Zadzwoń do nas
            </a> 
        </div>
        <div class="lg:mt-0 lg:col-span-6 lg:flex lg:items-end">
            <img src="./assets/Hero.png" alt="Auta" class="offset-bottom">
        </div>                
    </div>
</section>

<section>
  <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16 lg:px-6">
      <div class="max-w-screen-lg text-gray-500 sm:text-lg dark:text-gray-400">
            <h3 class="mb-3">Prezentacja firmy</h3>
          <h2 class="mb-7 tracking-tight text-gray-900 dark:text-white">Zobacz naszą galerię zdjęć</h2>
          <a href="#" class="inline-flex items-center hover:font-medium text-primary-600 hover:text-primary-800">
              Samochody osobowe
              <svg class="ml-1 w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd"></path></svg>
          </a>
          <a href="#" class="inline-flex items-center font-medium text-primary-600 hover:text-primary-800">
              Samochody dostawcze
              <svg class="ml-1 w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd"></path></svg>  
          </a>
      </div>
  </div>
</section>

    <main class = "container mx-auto max-w-screen-xl">
        
        <vueper-slides
            class="no-shadow"
            :visible-slides="2"
            slide-multiple
            :slide-ratio="1 / 4"
            :gap="5"
            :arrows-outside="false">
                <vueper-slide 
                v-for="(slide, i) in slides" 
                :key="i"
                :image = "slide.image"  />
        </vueper-slides>
    </main>

    <!--Footer container-->
    <footer
        class="flex flex-col items-center bg-neutral-800 text-white text-center text-surface lg:text-left">
        <div class="container p-6 mx-auto max-w-screen-xl">
            <div class="grid gap-4 lg:grid-cols-2">
                <div class="mb-6 md:mb-0">
                <h5 class="mb-2">Id nostrud enim esse consectetur in eu mollit fugiat aute. Velit nulla commodo.</h5>

                <p class="mb-4 font">
                  Mauris varius ipsum mauris, 
                  rutrum lobortis magna efficitur a. 
                  Donec egestas, nisl vehicula feugiat 
                  ornare, diam turpis efficitur mi, ac 
                  venenatis eros ipsum ac arcu. Vestibulum et  [...]
        </p>
      </div>

      <div class="mb-6 md:mb-0">
        <h5 class="mb-2 font-medium uppercase">Footer text</h5>

        <p class="mb-4">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Iste
          atque ea quis molestias. Fugiat pariatur maxime quis culpa
          corporis vitae repudiandae aliquam voluptatem veniam, est atque
          cumque eum delectus sint!
        </p>
        <button class="text-primary-600 hover:text-primary-800 dark:text-primary-500 dark:hover:text-primary-700">Expand</button>
      </div>
    </div>
  </div>

  <!--Copyright section-->
  <div class="w-full bg-black/5 p-4 text-center">
    © 2023 Copyright:
    <a href="https://tw-elements.com/">TW Elements</a>
  </div>
    </footer>

</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Roboto+Condensed:wght@400;500;700&family=Roboto+Flex:wght@400;500;700&display=swap');

body{
  font-family: 'Roboto Condensed';
  font-weight: 400;
  font-size: 16px;
}

h1 {
  font-family: 'Bebas Neue', sans-serif;
  font-size: 76.29px;
}

h2 {
  font-family: 'Bebas Neue', sans-serif;
  font-size: 40px;
}

h3 {
  font-family: 'Roboto Condensed';
  font-weight: 400;
  font-size: 21.5px;
}

h5 {
  font-family: 'Bebas Neue', sans-serif;
  font-size: 25px;
}

button, a {
  font-family: 'Roboto Flex';
}

.original-size {
    width: 200%;
    height: auto;
}

.offset-bottom {
    position: relative;
    top: 100px; 
}

</style>
