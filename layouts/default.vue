<template>
  <!--<v-app>-->
    <div>
      <v-toolbar>
        <v-app-bar-nav-icon></v-app-bar-nav-icon>
        <v-toolbar-title>NuxtJs Tutorial</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-toolbar-items class="hidden-sm-and-down">
          <v-btn text><n-link to="/">Home</n-link></v-btn>
          <v-btn text><n-link to="/about">About</n-link></v-btn>
          <v-btn text><n-link to="/inspire">Inspire</n-link></v-btn>
        </v-toolbar-items>
      </v-toolbar>
      <nuxt/>
    </div>
  <!--</v-app>-->
</template>

