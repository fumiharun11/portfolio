<template>
  <v-container class="grey lighten-3">
    <v-row>
      <v-col cols="6">
        <v-layout justify-center align-center>
          <Thumbnail />
        </v-layout>
      </v-col>
      <v-col cols="6">
        <v-layout justify-center align-center>
          <h3>Welcome to</h3>
        </v-layout>
        <v-layout justify-center align-center>
          <h1>Miharun's Portfolio</h1>
        </v-layout>
        <v-divider class="my-5"></v-divider>
        <v-layout justify-center align-center>
          <v-btn x-large depressed class="secondary">Profile</v-btn>
        </v-layout>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import Thumbnail from "~/components/Thumbnail.vue";

export default {
  components: {
    Thumbnail,
  },
};
</script>
