<template>
  <v-app-bar app color="green-accent-3" :elevation="2" class="custom-height-bar">
    <template v-slot:prepend>
      <v-app-bar-nav-icon />
    </template>

    <v-container class="ma-1 pa-0">
      <span class="top-navifation-logo">Q²</span>
    </v-container>


    <template v-slot:append>
      <v-btn icon="mdi-heart"></v-btn>

      <v-btn icon="mdi-magnify"></v-btn>

      <v-btn icon="mdi-dots-vertical"></v-btn>
    </template>
  </v-app-bar>
</template>

<script>
export default {

}
</script>

<style>
.top-navifation-logo {
  font-family: 'Protest Guerrilla';
}
</style>