<script>
import AppSectionSubject from "./AppSectionSubject.vue";
import AppSection1 from "./AppSection1.vue";
import AppSection2 from "./AppSection2.vue";
export default {
    name: `AppMain`,
    components:{
      AppSectionSubject,
      AppSection1,
      AppSection2
    }
}
</script>

<template>
  <div class="container">
    <AppSectionSubject/>
    <AppSection1/>
    <AppSection2/>
  </div>
</template>

<style>
.container{
  padding-left: 100px;
  padding-right: 100px;
}
</style>