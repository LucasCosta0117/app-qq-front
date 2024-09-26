<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title>My Application</v-toolbar-title>
    </v-app-bar>

    <v-navigation-drawer app>
      <v-list>
        <v-list-item @click="$router.push('/')">
          <v-list-item-title>Home</v-list-item-title>
        </v-list-item>
        <v-list-item @click="$router.push('/about')">
          <v-list-item-title>About</v-list-item-title>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>

    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',
}
</script>
