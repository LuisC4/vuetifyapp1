<template>
  <div id="app">
    <v-app id="inspire">
    <v-navigation-drawer
    app
    v-model="drawer">
      <v-list-item>
        <v-list-item-content>
          <v-list-item-title class="title">
            Application
          </v-list-item-title>
          <v-list-item-subtitle>
            subtext
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
        >
          <v-list-item-icon>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title>{{ item.title }}</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>

     <!-- 
       APP BAR:
      -->
    <div>
    <v-app-bar app id="appbarmain"
      color="deep-purple accent-4"
      dense
      dark
    >
      <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>

      <v-toolbar-title>Page title</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-heart</v-icon>
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
          { title: 'Sobre Nosotros', icon: 'mdi-help-box', path: '/About'},
          { title: 'Series y Peliculas', icon: 'mdi-help-box', path: '/SeriesPeliculas'},
          { title: 'Musica', icon: 'mdi-help-box', path: '/Musica'},
          { title: 'Game Streaming Platforms', icon: 'mdi-help-box', path: '/StreamingJuegos'},
          { title: 'Gloud Gaming', icon: 'mdi-help-box', path: '/CloudGaming'}
        ],
        right: null,
         }),
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
