<script>
import AppMain from "./components/AppMain.vue";
import AppHeader from "./components/AppHeader.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  name: "App",
  components :{
    AppHeader,
    AppMain,
    AppFooter
    
  },
}
</script>

<template>
  <AppMain/>
  <AppHeader/>
  <AppFooter/>
</template>

<style>

</style>
