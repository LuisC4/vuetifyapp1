<template>
  <div id="GameStreaming">
    <v-container>
      <v-alert color="#2A3B4D" dark dense>
        <h1>Streaming</h1>
        <p class="text-left">
        El streaming (traducido como retransmisión en directo), lectura en continuo, difusión en continuo, descarga continua) es la distribución digital de contenido multimedia a través de una red de computadoras, de manera que el usuario utiliza el producto a la vez que se descarga. La palabra retransmisión se refiere a una corriente continua que fluye sin interrupción, y habitualmente a la difusión de audio o vídeo. Este tipo de tecnología funciona mediante un búfer de datos que va almacenando el flujo de descarga en la estación del usuario para mostrarle de inmediato el material descargado. Esto se contrapone al mecanismo de descarga de archivos.
        </p>
        <h3 class="mt-3 text-h5">¿Qué es streaming gamer?</h3>
        <p class="text-left">
            Es el lugar donde amantes de los videojuegos retransmiten en directo sus partidas, dialogando con sus seguidores mediante el chat en vivo y con los que pueden interactuar, brindándoles contenidos exclusivos previa aportación económica a modo de donación o suscripción.
        </p>
        <h3>Algunas plataforma de Streaming gamer son:</h3>
      </v-alert>

      <v-row>
        <!-- CARD TWITCH -->
          <v-card  class="mx-lg-auto mx-sm-6 my-12" max-width="374">
            <template slot="progress">
              <v-progress-linear
                color="purple lighten-2"
                height="10"
                indeterminate
              ></v-progress-linear>
            </template>
            <v-img
            
              height="250"
              src="../assets/twitch.jpg"
            ></v-img>
            <v-card-title class="text-h3">Twitch</v-card-title>
            <v-card-text class="text-sm-body-2 text-md-body-1 text-xl-h6 text-justify">
                Twitch es una plataforma que permite realizar transmisiones en
                vivo, la cual es propiedad de Amazon, Inc., esta plataforma
                tiene como función principal la retransmisión de videojuegos en
                directo, un campo en el que tiene como competidor a YouTube.
            </v-card-text>
            <v-divider class="mt-10"></v-divider>
            <v-card-actions>
              <v-btn
                href="https://www.twitch.tv/"
                target="_blank"
                color="deep-purple darken-1"
                text
              >
                Pagina
              </v-btn>
            </v-card-actions>
          </v-card>

            <!-- CARD YOUTUBE GAMING -->
          <v-card  class="mx-lg-auto mx-sm-12 my-12" max-width="374">
            <template slot="progress">
              <v-progress-linear
                color="deep-purple"
                height="10"
                indeterminate
              ></v-progress-linear>
            </template>
            <v-img
              height="250"
              src="../assets/youtubeG.png"
            ></v-img>
            <v-card-title class="text-h3">YouTube</v-card-title>
            <v-card-text class="text-sm-body-2 text-md-body-1 text-xl-h6 text-justify">
                YouTube es un sitio web de origen estadounidense dedicado a compartir videos. Presenta una variedad de clips de películas, programas de televisión y vídeos musicales, así como contenidos amateur como videoblogs y YouTube Gaming
            </v-card-text>
            <v-divider class="mt-16"></v-divider>
            <v-card-actions>
              <v-btn
                href="https://www.youtube.com/gaming"
                target="_blank"
                color="red darken-1"
                text
              > Pagina
              </v-btn>
            </v-card-actions>
          </v-card>
          <!-- CARD FACEBOOK -->
          <v-card class="mx-lg-auto mx-sm-6 my-12" max-width="374">
        <template slot="progress">
          <v-progress-linear
            color="deep-purple"
            height="10"
            indeterminate
          ></v-progress-linear>
        </template>
        <v-img
          height="250"
          src="../assets/facebookG.png"
        ></v-img>
        <v-card-title class="text-h4">Facebook Gaming </v-card-title>
        <v-card-text class="text-sm-body-2 text-md-body-1 text-xl-h6 text-justify">
            Facebook Gaming ya es una realidad, una aplicación con la que la red social busca plantar cara a plataformas como Twitch. En esta aplicación los usuarios van a poder jugar a una selección de juegos o poder seguir a una serie de streamers de juegos que realizan retransmisiones en directo. Además de ser posible convertirse en un streamer también dentro de esta nueva plataforma.
        </v-card-text>
        <v-divider class="mx-4"></v-divider>
        <v-card-actions>
          <v-btn
            href="https://www.facebook.com/gaming/"
            target="_blank"
            color="blue darken-2"
            text
          >
            Pagina
          </v-btn>
        </v-card-actions>
      </v-card>
      </v-row>
    </v-container>
  </div>
</template>