<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },
  data() {
    return {
      menu: [
        "HOME",
        "ELEMENTS",
        "FEATURES",
        "PAGES",
        "PORTFOLIO",
        "BLOG",
        "SHOP"
      ]
    }
  }
}
</script>

<template> 

 <AppHeader />
 <AppMain />
 <AppFooter />

</template>

<style>

</style>
