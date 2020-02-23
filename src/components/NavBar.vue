<template>
  <div>
    <v-card class="overflow-hidden">
    </v-card>
    <v-app-bar
      id="header"
      :collapse="!collapseOnScroll"
      :collapse-on-scroll="collapseOnScroll"
      color="deep-purple accent-4"
      dark
      scroll-target="#scrolling-techniques-6"
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Alana's Blog</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-home</v-icon>
      </v-btn>

    </v-app-bar>
  </div>
</template>

<script>
  export default {
    name: "NavBar",
    data: () => ({
      collapseOnScroll: true,
    }),
  }
</script>

<style>
  #header {
    position: sticky;
    top: 0;
    z-index: 100;
  }
</style>