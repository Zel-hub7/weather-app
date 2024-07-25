<template>
  <div class="flex flex-col min-h-screen font-Roboto bg-weather-primary">
    <SiteNavigation />
    <RouterView />

  </div>
</template>

<script>
import SiteNavigation from "./components/SiteNavigation.vue";

import { RouterView } from 'vue-router';

export default {
  components: {
    SiteNavigation,
    RouterView,
   
  }
};
</script>

<style>
/* Add any necessary global styles here */
</style>
