<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Vuetify</span>
        <span class="font-weight-light">MATERIAL DESIGN</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn flat to="/" exact>Home</v-btn>
      <v-btn flat to="/about" exact>About</v-btn>
    </v-toolbar>
 
    <v-content>
    <v-layout text-xs-center wrap>
    <v-flex>
      <div id="nav">
	<br></br>
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
      </div>
      <router-view />
    </v-flex>
    </v-layout>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: "App",
  components: {},
  data() {
    return {
      //
    };
  }
};
</script>
