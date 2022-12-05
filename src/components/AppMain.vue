<script>
import AppSectionSubject from "./AppSectionSubject.vue";
export default {
    name: `AppMain`,
    components:{
      AppSectionSubject
    }
}
</script>

<template>
  <div class="container">
    <AppSectionSubject/>
  </div>
</template>

<style>
.container{
  padding-left: 30px;
  padding-right: 30px;
}
</style>