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
    <!-- PRIMER SHADOW -->
    <div id="Cloud__Shadow" class="mt-5">
    <v-row>
      <v-col md="8">
        <div>
        <h1>Shadow</h1>
        <p class="text-sm-body-2 text-md-body-1 text-xl-h6 text-left">Shadow es la empresa solitaria que presta un servicio realizado. En realidad, no ofrece juegos en la nube, pero ofrece juegos de computación en la nube. Siendo el único en el mercado, es, por defecto, el proveedor de juegos en la nube más recomendado por los consumidores. Ofrece una biblioteca de juegos gigantesca, juegos de alto rendimiento y un período de accesibilidad importante. Incluso con un gran ancho de banda con un ping bajo, se retrasa con respecto al desplazamiento y tiene problemas en la capacidad de respuesta del cursor.</p>
        <v-expansion-panels accordion>
      <v-expansion-panel>
        <v-expansion-panel-header class="text-sm-body-1 text-md-subtitle-1">Caracteristicas de este proveedor</v-expansion-panel-header>
        <v-expansion-panel-content class="text-sm-body-2 text-md-body-1 text-left">
          <ul>
            <li>Ofrece transmisión 4k en ultra alta definición sin problemas de latencia, aunque recomienda tener una conexión de un mínimo de 5 Mbps.</li>
            <li>El servicio de juegos en la sombra siempre está actualizado con la PC y utiliza una GPU dedicada para funcionar de la manera más impecable posible.</li>
            <li>Shadow ha considerado que los usuarios compartan archivos y carpetas con amigos o conocidos para crecer.</li>
            <li>Esta plataforma de juegos ofrece a sus clientes comprar almacenamiento; inicialmente, a partir de 256 GB, un usuario puede ampliar su almacenamiento a 2 TB.</li>
          </ul>

        </v-expansion-panel-content>
      </v-expansion-panel>
    </v-expansion-panels>
        </div>
      </v-col>
      <v-col md="4">
         <v-img
        contain
        src="../assets/Shadow.png"
      ></v-img>
    <v-btn
      depressed
      color="grey darken-3"
      class="mt-5"
      dark
      href="https://shadow.tech/" target="_blank"
    >
      Sitio Web
    </v-btn>
      </v-col>
    </v-row>
    
    </div>
    <!-- FIN PRIMER SHADOW -->
    <!-- SEGUNDO NVIDIA GEFORCE NOW-->
    <div id="Cloud__Nvidia" class="mt-10">
    <v-row>
      <v-col md="8">
        <div>
        <h1>Geforce Now</h1>
        <p class="text-sm-body-2 text-md-body-1 text-xl-h6 text-left">Geforce ofrece actualmente uno de los servicios de juegos en la nube más eficientes. Esta plataforma de juegos en la nube utiliza ultra streaming para no interrumpir y reducir la latencia. Con una sola cuenta, los servicios se pueden recibir a través de PC, Mac, Shield TV. Los precios de las suscripciones son bajos. Con solo un cargo de suscripción mensual de $9.99, uno puede disponer de 50 juegos más o menos.</p>
        <v-expansion-panels accordion>
      <v-expansion-panel>
        <v-expansion-panel-header class="text-sm-body-1 text-md-subtitle-1">Caracteristicas de este proveedor</v-expansion-panel-header>
        <v-expansion-panel-content class="text-sm-body-2 text-md-body-1 text-left">
          <ul>
            <li>Geforce ahora ofrece Ultra Streaming. Esto resuelve muy bien los problemas de latencia y permite la transmisión de 4k a 60 fps.</li>
            <li>Geforce ahora también es rentable, ya que se ejecuta en Shield TV, Shield Portable, Tablet y Mac.</li>
            <li>Con solo una suscripción de $9.99/mes, la variedad de juegos gratuitos es enorme. Actualmente, hay más de 400 títulos y se agregan regularmente.</li>
            <li>Geforce ahora está tratando de crecer según la demanda pública, ya que brinda a sus usuarios la accesibilidad para proporcionar solicitudes de funciones fácilmente.</li>
          </ul>
        </v-expansion-panel-content>
      </v-expansion-panel>
    </v-expansion-panels>
        </div>
      </v-col>
      <v-col md="4">
         <v-img
        contain
        src="../assets/Nvidia.png"
      ></v-img>
      <v-btn
      depressed
      color="green darken-4"
      class="mt-5"
      dark
      href="https://www.nvidia.com/en-us/geforce-now/" target="_blank"
    >
      Sitio Web
    </v-btn>
      </v-col>
    </v-row>
    </div>
    <!-- FIN SEGUNDO NVIDIA GEFORCE NOW-->

    <!-- TERCERO PROYECT XCLOUD-->
    <div id="Cloud__Xcloud" class="mt-10">
    <v-row>
      <v-col md="8">
        <div>
        <h1>PROYECT XCLOUD</h1>
        <p class="text-sm-body-2 text-md-body-1 text-xl-h6 text-left">Project Xcloud, encabezado por Microsoft, está preparado para convertirse en el próximo servicio superior de juegos en la nube en la plataforma de juegos en la nube, dejando atrás a Google Stadia Gaming Service incluso en versión beta. Actualmente, el proyecto Xcloud se encuentra en el período de vista previa. Puede ser utilizado por las personas que tienen la suerte de obtener una invitación como servicios gratuitos de juegos en la nube.</p>
        <v-expansion-panels accordion>
      <v-expansion-panel>
        <v-expansion-panel-header class="text-sm-body-1 text-md-subtitle-1">Caracteristicas de este proveedor</v-expansion-panel-header>
        <v-expansion-panel-content class="text-sm-body-2 text-md-body-1 text-left">
          <ul>
            <li>Project Xcloud tiene el procedimiento de registro más fácil, pero Microsoft ofrece invitaciones a algunos jugadores para el período de vista previa.</li>
            <li>Los beneficios de la continuidad. Un usuario puede apagar una pantalla y comenzar a jugar en la pantalla de otro dispositivo justo donde el usuario lo dejó.</li>
            <li>Utiliza el sistema de redes masivo de Azure. Los centros de datos de Azure se distribuyen por América del Norte, Asia y Europa.</li>
            <li>Viene con algunos entrecortes menores, pero promete una transmisión fluida de juegos en la nube si el WIFI tiene un mínimo de 5Ghz</li>
          </ul>

        </v-expansion-panel-content>
      </v-expansion-panel>
    </v-expansion-panels>
        </div>
      </v-col>
      <v-col md="4">
         <v-img
        contain
        src="../assets/xcloud.jpg"
      ></v-img>
      <v-btn
      depressed
      class="mt-5"
      href="https://www.xbox.com/en-IN/xbox-game-streaming/project-xcloud" target="_blank"
    >
      Sitio Web
    </v-btn>
      </v-col>
    </v-row>
    </div>
    <!-- FIN TERCERO PROYECT XCLOUD-->

    <!-- CUARTO Playkey-->
    <div id="Cloud__Playkey" class="mt-10">
    <v-row>
      <v-col md="8">
        <div>
        <h1>Playkey</h1>
       <p class="text-sm-body-2 text-md-body-1 text-xl-h6 text-left">Playkey permite a los usuarios conectarse a sus servidores de juegos a través de cualquier dispositivo moderno a través de Internet. La iniciativa para seguir adelante con la clave de juego fue en el año 2013. Playkey.net planea proporcionar a los jugadores la solución para no tener hardware más reciente o de alta gama en su PC y aún ejecutar juegos de alta gama. Los juegos como GTA V se ejecutan a través de sus servicios en la nube sin problemas de retraso. Puedes jugar desde $1 por hora</p>
        <v-expansion-panels accordion>
      <v-expansion-panel>
        <v-expansion-panel-header class="text-sm-body-1 text-md-subtitle-1">Caracteristicas de este proveedor</v-expansion-panel-header>
        <v-expansion-panel-content class="text-sm-body-2 text-md-body-1 text-left">
          <ul>
            <li>Para impulsar a los consumidores, Playkey permite a los nuevos titulares de cuentas una demostración de juego gratuita de 20 minutos.</li>
            <li>Una PC de consumo puede tener especificaciones tan bajas como un procesador de 1,5 GHz, 1 GB de RAM, Windows 7, 8, 10, Mac OS 10.8 y ejecutar los servicios de Playkey.</li>
            <li>En una conexión a Internet de baja velocidad como 10 Mbps, los consumidores pueden ejecutar juegos en HD a 30 fps.</li>
            <li>Una conexión de 5Ghz proporciona una conexión optimizada y Playkey el cual proporciona una experiencia de juego a 1080p a 60 fps como máximo.</li>
          </ul>

        </v-expansion-panel-content>
      </v-expansion-panel>
    </v-expansion-panels>
        </div>
      </v-col>
      <v-col md="4">
         <v-img
        contain
        src="../assets/playkey.png"
      ></v-img>
      <v-btn
      depressed
      color="light-blue darken-4"
      class="mt-5"
      dark
      href="https://welcome.playkey.net/en/lp/intro-ww-quiz-offer/" target="_blank"
    >
      Sitio Web
    </v-btn>
      </v-col>
    </v-row>
    </div>
    <!-- FIN CUARTO Playkey-->
      </v-container>


    </div>
</template>
<script>
export default {
   data: () => ({
  }),
}
</script>