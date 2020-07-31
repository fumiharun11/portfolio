<template>
  <v-container>
    <v-row>
      <v-col cols="6">
        <v-layout justify-center align-center>
          <Thumbnail />
        </v-layout>
      </v-col>
      <v-col cols="6">
        <v-layout justify-center align-center>
          <div class="text-h6">Welcome to</div>
        </v-layout>
        <v-layout justify-center align-center>
          <div class="text-h4">Miharun's Portfolio</div>
        </v-layout>
        <v-divider class="my-5"></v-divider>
        <v-layout justify-center align-center>
          <div class="text-body-2 mb-3">If you want to know about me, please click the button below.</div>
        </v-layout>
        <v-layout justify-center align-center>
          <v-btn x-large depressed class="secondary text-button">Profile</v-btn>
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
