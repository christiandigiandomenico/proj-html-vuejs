<script>

import AppNav from './components/AppNav.vue';
import AppJumbo from './components/AppJumbo.vue';

export default {

  data() {
        return {
            linksNav: ["Home", "Shop", "Blog", "Media", "ShortCodes", "Features"],
        }
    },

components: {
  AppNav,
  AppJumbo,
}

}

</script>

<template>

  <AppNav :links="linksNav"></AppNav>

  <AppJumbo></AppJumbo>
  
</template>

<style>

</style>
