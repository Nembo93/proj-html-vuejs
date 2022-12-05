<script>
import store from "../src/store.js"
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

  data (){
    return{
      store
    }
  }
}
</script>

<template>
  <AppMain/>
  <AppHeader/>
  <AppFooter/>
</template>

<style>

</style>
