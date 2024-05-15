<template>
  <v-app id="inspire">
    <v-app-bar class="bg-blue-grey-darken-4">
      <v-app-bar-nav-icon ></v-app-bar-nav-icon>

      <v-app-bar-title class="text-yellow font-wieght-black">SAMovie</v-app-bar-title>
    </v-app-bar>
    <v-main class="bg-blue-grey-darken-4">
      <v-img
            class="bg-white"
            src="../assets/hero-bg.jpg"
            cover>
    <div class="text-yellow mt-30 ml-10">
    <h1 class="text-yellow mt-10 ml-11">SAMovie</h1>
          <h1 class="text-white mt-10 text-h2 font-wieght-black">
            Unlimited Movie, TVs Shows,
          <br> <span class="text-yellow mt-30 ml-10"> & More </span>
          </h1>
        </div>
          </v-img>
    </v-main>
    <v-main class="bg-blue-grey-darken-4">

      <v-img
            class="bg-white"
            src="../assets/service-bg.jpg"
            cover>
      <v-container>

        <v-row>

            <v-col
              class="mt-2"
              cols="3"
              v-for="mov in movies"
              :key="mov"
            >

  
            <v-img
            rounded
            :aspect-ratio="1"
            class="bg-red"
            src="../assets/movie-11.png"
            height="350"
            cover>
            </v-img>
            </v-col>
        </v-row>
      </v-container>
    </v-img>
    </v-main>
  </v-app>
</template>
  <script setup>
  
  const movies =[
    {
      movie : "movie-1",
      src : "../assets/movie-1.png"
    },
    {
      movie : "movie-2",
      src : "../assets/movie-2.png"
    },
    {
      movie : "movie-3",
      src : "../assets/movie-3.png"
    },
    {
      movie : "movie-4",
      src : "../assets/movie-4.png"
    },
    {
      movie : "movie-5",
      src : "../assets/movie-5.png"
    },
    {
      movie : "movie-6",
      src : "../assets/movie-6.png"
    },
    {
      movie : "movie-7",
      src : "../assets/movie-7.png"
    },
    {
      movie : "movie-8",
      src : "../assets/movie-8.png"
    },
    {
      movie : "movie-9",
      src : "../assets/movie-9.png"
    },
    {
      movie : "movie-10",
      src : "../assets/movie-10.png"
    },
    {
      movie : "movie-11",
      src : "../assets/movie-11.png"
    }
  ]
  </script>
