<template>
  <nav>
    <v-app-bar flat app>
      <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
      <v-app-bar-title class="text-uppercase gray-text">
        <span class="font-weight-light">Todo</span>
        <span>Ninja</span>
      </v-app-bar-title>
      <v-spacer></v-spacer>
      <v-btn text color="gray"
        ><span>Sign Out</span><v-icon right>mdi-logout</v-icon></v-btn
      >
    </v-app-bar>

    <v-navigation-drawer app v-model="drawer" class="primary">
      tes</v-navigation-drawer
    >
  </nav>
</template>

<script>
export default {
  name: "NavbarComp",
  data() {
    return {
      drawer: true,
    };
  },
};
</script>

<style>
</style>