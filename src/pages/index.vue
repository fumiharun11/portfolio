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
          <h1>Welcome to Miharun's Portfolio</h1>
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
