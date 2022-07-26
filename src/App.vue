<template>
  <v-app>
    <app-navigation/>
    <v-main transition="slide-x-transition">
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>
import AppNavigation from './components/AppNavigation.vue'
export default {
  components: { AppNavigation },

}
</script>

<style>

</style>