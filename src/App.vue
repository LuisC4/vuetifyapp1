<template>
  <div id="app">
    <v-app id="inspire">
    <v-navigation-drawer
    app
    v-model="drawer"
            permanent
        expand-on-hover>
    
      <v-list-item>
        <v-list-item-content>
          <v-list-item-title class="title">
            <v-img src="./assets/gaming.svg" max-width="150"></v-img>
            Entretenimiento
          </v-list-item-title>
          <v-list-item-subtitle>
            Programacion IV
          </v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>

      <v-divider></v-divider>

      <v-list
        dense
        nav
      >
        <v-list-item
          v-for="item in items"
          :key="item.title"
          link
          :to="item.path"
           color="primary"
        >
          <v-list-item-icon>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title>{{ item.title }}</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
      <template v-slot:append>
        <div class="pa-2">
          <v-switch
        v-model="$vuetify.theme.dark"
        inset
        label="Tema Oscuro"
        persistent-hint
      ></v-switch>
        </div>
      </template>
    </v-navigation-drawer>

     <!-- 
       APP BAR:
      -->
    <div>
    <v-app-bar app id="appbarmain"
      absolute
    >

      <v-toolbar-title>Entretenimiento</v-toolbar-title>

      <v-spacer></v-spacer>
      <v-btn href="https://github.com/LuisC4/vuetifyapp1" target="_blank">
        <v-icon class="mr-3">mdi-github</v-icon>
        Repositorio
      </v-btn>
    </v-app-bar>
  </div>

    <v-main>
      <!--  -->
      <router-view/>
    </v-main>

    <v-footer padless>
    <v-col
      class="text-center"
      cols="12"
    >
      {{ new Date().getFullYear() }} — <strong>Primera app con Vuetify</strong>
    </v-col>
  </v-footer>
  </v-app>
    
  </div>
</template>

<script>
export default {
   data: () => ({ 
     drawer: null,
     items: [
          { title: 'Dashboard', icon: 'mdi-view-dashboard', path: '/' },
          { title: 'Series y Peliculas', icon: 'mdi-movie-open', path: '/SeriesPeliculas'},
          { title: 'Musica', icon: 'mdi-music-circle', path: '/Musica'},
          { title: 'Game Streaming', icon: 'mdi-gamepad-square', path: '/StreamingJuegos'},
          { title: 'Gloud Gaming', icon: 'mdi-cloud', path: '/CloudGaming'},
          { title: 'Sobre Nosotros', icon: 'mdi-account-box-multiple', path: '/About'}
        ],
        right: null,
         }),
}
</script>

<style lang="scss">
#app {
  font-family: 'Josefin Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>
