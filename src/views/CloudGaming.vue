<template>
    <div id="CloudGaming">
      <v-container>
        <v-alert
      border="left"
      colored-border
      color="deep-purple accent-4"
      elevation="2"
    >
      <h1 class="text-sm-h3 text-lg-h3">Como Funciona el Cloud Gaming?</h1>
      <p class="text-justify text-sm-body-2 text-lg-h6 ">Los juegos se almacenan, inician y procesan en servidores remotos ubicados en centros de datos al rededor del mundo. Recibirá una videostream interactiva en su dispositivo. ¡Así que ejecutar un software de alta gama es tan fácil para su dispositivo como una reproducción de video!
        <br> <br>
      Cada movimiento y cada clic que realizas se codifica, se envía a nuestros servidores, se procesa y se te devuelve decodificado. ¡Todo sucede al instante para que ni siquiera te des cuenta de que los servidores reales que procesan tu juego se encuentran a muchos kilómetros de distancia!</p>
      <template>
      <v-row justify="center">
        <v-col md="4">
            <v-img
        lazy-src="https://picsum.photos/id/11/10/6"
        contain
        max-height="300"
        max-width="400"
        src="../assets/left.svg"
      ></v-img>
      </v-col>
      <v-col md="4">
      <v-img
        contain
        lazy-src="https://picsum.photos/id/11/10/6"
        max-height="300"
        max-width="400"
        src="../assets/right.svg"
      ></v-img>
      </v-col>
      </v-row>
      </template>
        </v-alert>
      <v-alert
      border="top"
      colored-border
      color="primary"
      elevation="2"
      class="font-italic text-sm-body-2 text-lg-h5 "
    >
      EL PODER DE TU HARDWARE YA NO IMPORTA, JUEGA DONDE ESTES Y EN EL DISPOSITIVO QUE TENGAS
    </v-alert>
    <v-alert
      border="right"
      colored-border
      color="red"
      elevation="3"
    >
    <h1 class="text-sm-h3 text-lg-h3">Principales plataformas de Cloud Gaming</h1>
    </v-alert>
      </v-container>
      
    </div>
</template>