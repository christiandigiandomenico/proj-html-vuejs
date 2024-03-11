<script>

import AppNav from './components/AppNav.vue';

export default {

  data() {
        return {
            linksNav: ["Home", "Shop", "Blog", "Media", "ShortCodes", "Features"],
        }
    },

components: {
  AppNav,
}

}

</script>

<template>

  <AppNav :links="linksNav"></AppNav>
  
</template>

<style>

</style>
