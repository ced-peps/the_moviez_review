<template>
  <div id="app">
    <v-row class="text-center">
      <v-col>
        <h1 class="font-weight-bold" style="text-align: center; height: 100px; color: white; background-color: #e4872c; padding-top:30px">
          The Moviez Review
        </h1>
      </v-col>
    </v-row>
    <div id="nav">
      <router-link to="/"><button style="border: 1px solid black; border-radius: 10px; height: 30px; width: 100px; background-color:#07305d; margin-right: 20px">Accueil</button></router-link>  
      <router-link to="/maListe"><button style="border: 1px solid black; border-radius: 10px; height: 30px; width: 100px; background-color:#07305d">Ma liste</button></router-link>
    </div>
    <router-view/>
  </div>
</template>

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
    color: white;

    &.router-link-exact-active {
      color: #f0bb86;
    }
  }
}
</style>
