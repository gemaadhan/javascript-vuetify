<template>
  <nav>
    <v-app-bar flat app>
      <v-app-bar-title class="text-uppercase gray-text">
        <span class="font-weight-light">Todo</span>
        <span>Ninja</span>
      </v-app-bar-title>
      <v-spacer></v-spacer>
      <v-btn text color="gray"
        ><span>Sign Out</span><v-icon right>mdi-logout</v-icon></v-btn
      >
    </v-app-bar>
  </nav>
</template>

<script>
export default {
  name: "NavbarComp",
};
</script>

<style>
</style>