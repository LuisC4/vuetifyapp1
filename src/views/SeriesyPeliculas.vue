<template>
  <div id="SeriesyPeliculas">
    <v-container>
      <v-alert color="#006064" dark dense>
        <h1>Series y Peliculas</h1>
        <p class="text-left text-sm-body-2 text-lg-h6 ">
          El streaming es básicamente la tecnología que nos permite visualizar
          un archivo de audio o vídeo sin descargarlo previamente a nuestro
          dispositivo, es decir, directamente desde Internet en una página web o
          una aplicación móvil y lo logramos ver a medida que se va descargando
          el contenido.
        </p>

        <p class="text-left"></p>
        <h3>
          Algunas plataform para ver series y películas vía streaming son:
        </h3>
      </v-alert>

      <v-row>
        <!-- CARD NETFLIX -->
        <v-card class="mx-lg-auto mx-sm-6 my-12" max-width="374">
          <template slot="progress">
            <v-progress-linear
              color="purple lighten-2"
              height="10"
              indeterminate
            ></v-progress-linear>
          </template>
          <v-img height="250" src="../assets/Netflix.jpg"></v-img>
          <v-card-title class="text-h3">NETFLIX</v-card-title>
          <v-card-text
            class="text-sm-body-2 text-md-body-1 text-xl-h6 text-justify"
          >
            cuenta con un catálogo casi ilimitado a un precio muy asequible o
            frece algunas de las series mejor valoradas de los últimos tiempos,
            como por ejemplo House of Cards. Su propuesta en varios idiomas
            (inglés, francés, español, alemán e italiano) hace que esté presente
            en varios países y que se ajuste a las preferencias de cada uno un
            pequeño punto en contra es que su catálogo presenta grandes
            diferencias según en qué país se consuma.
          </v-card-text>
          <v-divider class="mt-10"></v-divider>
          <v-card-actions>
            <v-btn
              href="https://www.netflix.com/browse"
              target="_blank"
              color="red darken-4"
              text
            >
              Pagina
            </v-btn>
          </v-card-actions>
        </v-card>

        <!-- HBO -->
        <v-card class="mx-lg-auto mx-sm-6 my-12" max-width="374">
          <template slot="progress">
            <v-progress-linear
              color="deep-purple"
              height="10"
              indeterminate
            ></v-progress-linear>
          </template>
          <v-img height="250" src="../assets/hbo.png"></v-img>
          <v-card-title class="text-h3">HBO</v-card-title>
          <v-card-text
            class="text-sm-body-2 text-md-body-1 text-xl-h6 text-justify"
          >
            con grandes títulos como Juego de tronos o Los Soprano es HBO está
            plataforma también ofrece un amplio contenido de series tanto
            galardonadas como de producción propiaestá plataforma también ofrece
            un amplio contenido de series tanto galardonadas como de producción
            propia está plataforma también ofrece un amplio contenido de series
            tanto galardonadas como de producción propia.
          </v-card-text>
          <v-divider class="mt-16"></v-divider>
          <v-card-actions>
            <v-btn
              href="https://www.hbolatam.com/us/movies"
              target="_blank"
              color="purple darken-4"
              text
            >
              Pagina
            </v-btn>
          </v-card-actions>
        </v-card>

        <!-- Amazon Prime Video -->
        <v-card class="mx-lg-auto mx-sm-6 my-12" max-width="374">
          <template slot="progress">
            <v-progress-linear
              color="deep-purple"
              height="10"
              indeterminate
            ></v-progress-linear>
          </template>
          <v-img height="250" src="../assets/AmazonPrimeVideo.png"></v-img>
          <v-card-title class="text-h4">Amazon Prime Video </v-card-title>
          <v-card-text
            class="text-sm-body-2 text-md-body-1 text-xl-h6 text-justify"
          >
            Amazon Prime viene pisando fuerte tienes la posibilidad de disfrutar
            de su plataforma de streaming completamente gratis y si no, por solo
            36€ al año puedes tener acceso a todos sus contenidos. Al igual que
            las anteriores, Amazon Prime Video propone títulos de series muy
            variados y contenidos exclusivos.
          </v-card-text>
          <v-divider class="mx-4"></v-divider>
          <v-card-actions>
            <v-btn
              href="https://www.primevideo.com"
              target="_blank"
              color=" amber darken-4"
              text
            >
              Pagina
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-row>

      <v-row>
        <!-- CARD SKY -->
        <v-card class="mx-lg-auto mx-sm-6 my-12" max-width="374">
          <template slot="progress">
            <v-progress-linear
              color="purple lighten-2"
              height="10"
              indeterminate
            ></v-progress-linear>
          </template>
          <v-img height="250" src="../assets/sky.png" contain></v-img>
          <v-card-title class="text-h3">Sky TV</v-card-title>
          <v-card-text
            class="text-sm-body-2 text-md-body-1 text-xl-h6 text-justify"
          >
            Lo que la diferencia de las plataformas mencionadas anteriormente,
            es que SKY TV además de ofrecerte un extenso catálogo de series
            también te permite, a través de una suscripción de unos 7€ en
            España, tener acceso a canales de televisión de pago sin necesidad
            de contratar ningún paquete televisivo.
          </v-card-text>
          <v-divider class="mt-10"></v-divider>
          <v-card-actions>
            <v-btn
              href="https://www.sky.com/"
              target="_blank"
              color="red darken-4"
              text
            >
              Pagina
            </v-btn>
          </v-card-actions>
        </v-card>

        <!-- MOVISTAR -->
        <v-card class="mx-lg-auto mx-sm-6 my-12" max-width="374">
          <template slot="progress">
            <v-progress-linear
              color="deep-purple"
              height="10"
              indeterminate
            ></v-progress-linear>
          </template>
          <v-img height="250" src="../assets/movistar.png" contain></v-img>
          <v-card-title class="text-h3">MOVISTAR +</v-card-title>
          <v-card-text
            class="text-sm-body-2 text-md-body-1 text-xl-h6 text-justify"
          >
            Movistar + se ha convertido en una plataforma muy popular para ver
            contenidos online. En cuanto a series, ha apostado muy fuerte, como
            las demás, en hacer producciones propias. Mira lo que has hecho o
            Vergüenza son algunas de ellas. Por otro lado, dispone de
            programación de calidad y de un atractivo y amplio catálogo
          </v-card-text>
          <v-divider class="mt-16"></v-divider>
          <v-card-actions>
            <v-btn
              href="https://ver.movistarplus.es/"
              target="_blank"
              color="purple darken-4"
              text
            >
              Pagina
            </v-btn>
          </v-card-actions>
        </v-card>

        <!-- Disney+ -->
        <v-card class="mx-lg-auto mx-sm-6 my-12" max-width="374">
          <template slot="progress">
            <v-progress-linear
              color="deep-purple"
              height="10"
              indeterminate
            ></v-progress-linear>
          </template>
          <v-img height="250" src="../assets/disney.jpg" contain></v-img>
          <v-card-title class="text-h4">Disney+ </v-card-title>
          <v-card-text
            class="text-sm-body-2 text-md-body-1 text-xl-h6 text-justify"
          >
            Es la nueva plataforma del gigante del entretenimiento que ya se
            encuentra disponible en Estados Unidos y que muy pronto estará
            disponible en toda Europa. En Disney Plus podrás conseguir todo el
            contenido oficial de Marvel Studios, Lucasfilms, 20th Century
            Studios, series comos Los Simpsons, además de todo el catalogo
            tradicional de series y películas de la propia Walt Disney Studios.
          </v-card-text>
          <v-divider class="mx-4"></v-divider>
          <v-card-actions>
            <v-btn
              href="https://www.disneyplus.com/"
              target="_blank"
              color=" amber darken-4"
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
