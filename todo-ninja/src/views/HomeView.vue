<template>
  <div class="home">
    <h1>This is an home page</h1>
    <v-btn class="pink white--text">Pencet AKu</v-btn>

    <v-btn depressed color="pink" dark>click me</v-btn>
    <v-btn text color="pink">dudul aku</v-btn>

    <v-btn depressed class="pink white--text">
      <v-icon left>mdi-instagram</v-icon>
      <span>Follow us</span>
    </v-btn>

    <v-btn depressed small class="pink white--text">
      <v-icon small left>mdi-instagram</v-icon>
      <span>Follow us</span>
    </v-btn>

    <v-btn depressed large class="pink white--text">
      <span>Follow us</span>
      <v-icon large right>mdi-instagram</v-icon>
    </v-btn>

    <v-btn fab small dark color="purple">
      <v-icon>mdi-whatsapp</v-icon>
    </v-btn>
  </div>
</template>

<script>
export default {
  name: "HomePage",
};
</script>
