<template>
  <v-app dark>
    <v-app-bar clipped-left app>
      <v-toolbar-title v-text="title" />
    </v-app-bar>
    <v-main>
      <v-container>
        <nuxt />
      </v-container>
    </v-main>
    <v-footer :fixed="true" app>
      <v-layout justify-center>
        <span>&copy; {{ currentYear }} Haruki Fumino.</span>
      </v-layout>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      title: "Miharun's Portfolio",
      currentYear: new Date().getFullYear(),
    };
  },
};
</script>
