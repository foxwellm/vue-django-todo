<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view /> -->
  <v-app>
    <v-app-bar app color="deep-purple" dark>
      <div class="d-flex align-center">
        <v-toolbar-title>Todo App</v-toolbar-title>
      </div>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>
