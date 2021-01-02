<template>
  <v-app dark>
    <v-app-bar :clipped-left="clipped" fixed app>
      <v-spacer></v-spacer
      ><v-toolbar-title class="app-bar-title" v-text="title" />
      <v-spacer></v-spacer>
    </v-app-bar>
    <v-main class="main-container">
      <v-container class="inner-container">
        <nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      links: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/',
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire',
        },
      ],
      title: `💻 Portfolio de Manu`,
    }
  },
}
</script>

<style scoped>
.app-bar-title {
  margin-left: 1rem;
}
.app-bar-title:hover {
  text-decoration: underline;
  cursor: pointer;
}
</style>
