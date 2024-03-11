<script>

import AppNav from './components/AppNav.vue';
import AppJumbo from './components/AppJumbo.vue';
import AppMain from './components/AppMain.vue';

export default {

  data() {
        return {
            linksNav: ["Home", "Shop", "Blog", "Media", "ShortCodes", "Features"],
        }
    },

components: {
  AppNav,
  AppJumbo,
  AppMain,
}

}

</script>

<template>

  <AppNav :links="linksNav"></AppNav>

  <AppJumbo></AppJumbo>

  <AppMain></AppMain>
  
</template>

<style>

</style>
