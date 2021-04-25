<template>
  <div class="home">
    <v-container class="mb-8">
  <v-img class="mb-5"
  position="center center"
  max-height="300"
  max-width="1920"
  src="../assets/Home_img1.svg"
></v-img>
      <v-divider class="mt-5 mb-5"></v-divider>
    </v-container>

    <v-row justify="space-around">
      <div>
        <v-btn color="error" fab x-large dark to="SeriesPeliculas">
          <v-icon>mdi-movie-open</v-icon>
        </v-btn>
        <h1 class="mt-5">Series y Peliculas</h1>
        <v-btn class="mt-5" elevation="3" outlined rounded text to="SeriesPeliculas"
          >Series y Peliculas</v-btn
        >
      </div>

      <div>
        <v-btn color="success" fab x-large dark to="Musica">
          <v-icon>mdi-music-circle</v-icon>
        </v-btn>
        <h1 class="mt-5">Musica</h1>
        <v-btn class="mt-5" elevation="3" outlined rounded text to="Musica">Musica</v-btn>
      </div>

      <div>
        <v-btn color="warning" fab x-large dark to="StreamingJuegos">
          <v-icon>mdi-gamepad-square</v-icon>
        </v-btn>
        <h1 class="mt-5">Game Streaming</h1>
        <v-btn class="mt-5" elevation="3" outlined rounded text to="StreamingJuegos"
          >Game Streaming</v-btn
        >
      </div>

      <div>
        <v-btn color="primary" fab x-large dark to="CloudGaming">
          <v-icon>mdi-cloud</v-icon>
        </v-btn>
        <h1 class="mt-5">Cloud Gaming</h1>
        <v-btn class="mt-5" elevation="3" outlined rounded text to="CloudGaming"
          >Cloud Gaming</v-btn
        >
      </div>
    </v-row>
    <div class="mt-10 mb-5">
        <v-btn color="dark" fab x-large dark to="About">
          <v-icon>mdi-account-box-multiple</v-icon>
        </v-btn>
        <h1 class="mt-3">Equipo</h1>
        <v-btn class="mt-3" elevation="3" outlined rounded text to="About"
          >Sobre Nosotros</v-btn
        >
      </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
};
</script>

<style scoped>
.home {
  margin-top: 1%;
}
</style>
