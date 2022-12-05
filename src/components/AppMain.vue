<script>
import AppSectionSubject from "./AppSectionSubject.vue";
import AppSection1 from "./AppSection1.vue";
export default {
    name: `AppMain`,
    components:{
      AppSectionSubject,
      AppSection1
    }
}
</script>

<template>
  <div class="container">
    <AppSectionSubject/>
    <AppSection1/>
  </div>
</template>

<style>
.container{
  padding-left: 30px;
  padding-right: 30px;
}
</style>