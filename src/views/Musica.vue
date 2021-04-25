<template>
  <div id="Musica" class="mt-10 mb-5">
    <v-container class="mb-7">
    <v-alert
      border="left"
      colored-border
      color="deep-purple accent-4"
      elevation="2"
    >
      <h1 class="text-sm-h3 text-lg-h3">Servicios de Streaming de Musica</h1>
      <p class="text-justify text-sm-body-2 text-lg-h6 ">Son aquellas que te permiten reproducir audio o vídeo de forma continua, sin necesidad de descargar los archivos y algunas incluso, sin estar conectado a internet. Literalmente te permiten llevar toda tu música siempre contigo.
        <br> <br>
      Existen plataformas de pago, algunas gratuitas basadas en publicidad, pero todas ellas con características similares: te permiten reproducir en cualquiera de tus dispositivos, integrarse con otros sistemas, crear tus propias bibliotecas y descubrirte todas las novedades gracias a sus algoritmos, que aprenden de tus hábitos.</p>
        </v-alert>
        </v-container>
    <v-row justify="space-around" class="ml-5">
      <!-- Card 1 Spotify -->
      <v-card elevation="1" outlined shaped width="380">
        <v-img max-width="380" max-height="400" src="../assets/spotify.jpg"></v-img>
        <v-divider></v-divider>
        <v-card-title>
          <h2>Spotify</h2>
        </v-card-title>
        <v-card-text>
          <p class="text-sm-body-2 text-md-body-1 text-xl-h6 text-justify">
            Millones de canciones te esperan. Encuentra la mejor variedad de música para cada momento y escúchala desde tu ordenador, móvil o tablet. Haz listas con tus temas favoritos y compártelas con tus amigos.
          <br>
          </p>
        </v-card-text>
        <v-divider></v-divider>
        <v-card-actions>
          <v-btn
            rounded
            text
            href="https://www.spotify.com/sv/premium/"
            target="_blank"
          >
            Sitio Web
          </v-btn>
        </v-card-actions>
      </v-card>

      <!-- Card 2 Deezer -->
      <v-card elevation="1" outlined shaped max-width="380">
        <v-img max-width="380" max-height="400" src="../assets/deezer.jpg"></v-img>
        <v-divider></v-divider>
        <v-card-title>
          <h2>Deezer</h2>
        </v-card-title>
        <v-card-text>
          <p class="text-sm-body-2 text-md-body-1 text-xl-h6 text-justify">
            Descubre más de 50 millones de canciones con Deezer. Crea tus propias listas y compártelas. Descubre artistas nuevos gracias a las recomendaciones personalizadas. Lleva la música donde quieras gracias a su total compatibilidad con todo tipo de dispositivos.
          </p>
        </v-card-text>
        <v-divider></v-divider>
        <v-card-actions>
          <v-btn rounded text href="https://www.deezer.com/mx/" target="_blank">
            Sitio Web
          </v-btn>
        </v-card-actions>
      </v-card>

      <!-- Card 3 Tidal -->
      <v-card elevation="1" outlined shaped max-width="380">
        <v-img contain src="../assets/tidal.jpg"></v-img>
        <v-divider></v-divider>
        <v-card-title>
          <h2>Tidal</h2>
        </v-card-title>
        <v-card-text>
          <p class="text-sm-body-2 text-md-body-1 text-xl-h6 text-justify">
            La plataforma de música en streaming de Coldplay, Madonna y Beyoncé llegó. Disfruta de un extenso catálogo con más de 25 millones de canciones de todo tipo. Dispone de una versión Hifi donde podrás disponer de música en alta fidelidad.
          </p>
        </v-card-text>
        <v-divider></v-divider>
        <v-card-actions>
          <v-btn rounded text href="https://tidal.com/" target="_blank">
            Sitio Web
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-row>
  </div>
</template>