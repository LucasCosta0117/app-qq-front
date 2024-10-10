<template>
  <v-app>
    <top-navigation-bar />

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
import TopNavigationBar from './components/TopNavigationBar.vue';


export default {
  name: 'App',
  components: {
    TopNavigationBar
  }
}
</script>
