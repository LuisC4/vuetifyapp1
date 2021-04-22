<template>
  <div id="GameStreaming">
    <h1>Game Streaming Platforms</h1>
    <h3>Jeremy Aguilar</h3>
    <v-container>
      <v-alert color="#2A3B4D" dark dense>
        <h1>Streaming</h1>
        <p>
        </p>
        El streaming (traducido como retransmisión en directo), lectura en continuo, difusión en continuo, descarga continua) es la distribución digital de contenido multimedia a través de una red de computadoras, de manera que el usuario utiliza el producto a la vez que se descarga. La palabra retransmisión se refiere a una corriente continua que fluye sin interrupción, y habitualmente a la difusión de audio o vídeo. Este tipo de tecnología funciona mediante un búfer de datos que va almacenando el flujo de descarga en la estación del usuario para mostrarle de inmediato el material descargado. Esto se contrapone al mecanismo de descarga de archivos.
        <h3 class="mt-3">¿Qué es streaming gamer?</h3>
        <p>
            Es el lugar donde amantes de los videojuegos retransmiten en directo sus partidas, dialogando con sus seguidores mediante el chat en vivo y con los que pueden interactuar, brindándoles contenidos exclusivos previa aportación económica a modo de donación o suscripción.
        </p>
        <h3>Algunas plataforma de Streaming gamer son:</h3>
      </v-alert>

      <v-row>
        <v-col>
          <v-card :loading="loading" class="mx-auto my-12" max-width="374">
            <template slot="progress">
              <v-progress-linear
                color="purple lighten-2"
                height="10"
                indeterminate
              ></v-progress-linear>
            </template>
            <v-img
              height="250"
              src="https://cdn.discordapp.com/attachments/583372464931995730/834515192821579837/twitch.jpg"
            ></v-img>
            <v-card-title>Twitch</v-card-title>
            <v-card-text>
              <div>
                Twitch es una plataforma que permite realizar transmisiones en
                vivo, la cual es propiedad de Amazon, Inc., esta plataforma
                tiene como función principal la retransmisión de videojuegos en
                directo, un campo en el que tiene como competidor a YouTube.
              </div>
            </v-card-text>
            <v-divider class="mx-4"></v-divider>
            <v-card-actions>
              <v-btn
                href="https://www.twitch.tv/"
                target="_blank"
                color="deep-purple lighten-2"
                text
                @click="Pagina"
              >
                Pagina
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>

        <v-col>
          <v-card :loading="loading" class="mx-auto my-12" max-width="374">
            <template slot="progress">
              <v-progress-linear
                color="deep-purple"
                height="10"
                indeterminate
              ></v-progress-linear>
            </template>
            <v-img
              height="250"
              src="https://cdn.discordapp.com/attachments/583372464931995730/834551201995292702/9wt5Vo0dJPAAAAAElFTkSuQmCC.png"
            ></v-img>
            <v-card-title>YouTube</v-card-title>
            <v-card-text>
              <div>
                YouTube es un sitio web de origen estadounidense dedicado a compartir videos. Presenta una variedad de clips de películas, programas de televisión y vídeos musicales, así como contenidos amateur como videoblogs y YouTube Gaming
              </div>
            </v-card-text>
            <v-divider class="mx-4"></v-divider>
            <v-card-actions>
              <v-btn
                href="https://www.youtube.com/"
                target="_blank"
                color="deep-purple lighten-2"
                text
                @click="Pagina"
              > Pagina
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
      <v-card :loading="loading" class="mx-auto my-12" max-width="374">
        <template slot="progress">
          <v-progress-linear
            color="deep-purple"
            height="10"
            indeterminate
          ></v-progress-linear>
        </template>
        <v-img
          height="250"
          src="https://cdn.discordapp.com/attachments/583372464931995730/834550400991887390/CfoT9CPsR9iPsR9iPsB9hP8JhP0I40WfgMqXSJgvPAPrwAAAABJRU5ErkJggg.png"
        ></v-img>
        <v-card-title>Facebook Gaming </v-card-title>
        <v-card-text>
          <div>
            Facebook Gaming ya es una realidad, una aplicación con la que la red social busca plantar cara a plataformas como Twitch. En esta aplicación los usuarios van a poder jugar a una selección de juegos o poder seguir a una serie de streamers de juegos que realizan retransmisiones en directo. Además de ser posible convertirse en un streamer también dentro de esta nueva plataforma.
          </div>
        </v-card-text>
        <v-divider class="mx-4"></v-divider>
        <v-card-actions>
          <v-btn
            href="https://www.facebook.com/gaming/"
            target="_blank"
            color="deep-purple lighten-2"
            text
            @click="Pagina"
          >
            Pagina
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-container>
  </div>
</template>