<script>

import AppNav from './components/AppNav.vue';
import AppJumbo from './components/AppJumbo.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {

  data() {
        return {
            linksNav: ["Home", "Shop", "Blog", "Media", "ShortCodes", "Features"],
            linksFoot: ["Bookmark", "Features", "Sitemap", "Lists", "Contact Us"],
            linksFoot2: ["Delivery", "Cart", "Terms Condition", "My Account", "About Us"],
        }
    },

components: {
  AppNav,
  AppJumbo,
  AppMain,
  AppFooter,
}

}

</script>

<template>

  <AppNav :links="linksNav"></AppNav>

  <AppJumbo></AppJumbo>

  <AppMain></AppMain>

  <AppFooter :linksfooter="linksFoot" :linksfooter2="linksFoot2"></AppFooter>
  
</template>

<style>

</style>
