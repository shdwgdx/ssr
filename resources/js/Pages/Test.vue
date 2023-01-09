<template>
  <v-app>
    <v-navigation-drawer app> </v-navigation-drawer>

    <v-app-bar app color="#000000"> </v-app-bar>

    <v-main>
      <v-container fluid>
        <router-view></router-view>
      </v-container>
    </v-main>

    <v-footer app> </v-footer>
  </v-app>
</template>

<script>
export default {
  setup() {
    return {};
  },
  data() {
    return {
      range: [-5, 5],
    };
  },
};
</script>

<style lang="scss" scoped>
</style>