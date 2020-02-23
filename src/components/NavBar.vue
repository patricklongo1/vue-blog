<template>
  <div>
    <v-app-bar
      :collapse="!collapseOnScroll"
      :collapse-on-scroll="collapseOnScroll"
      scroll-target="#home"
      fixed
      color="deep-purple accent-4"
      dark
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-app-bar-title>Alana's Blog</v-app-bar-title>

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
