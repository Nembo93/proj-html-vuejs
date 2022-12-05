<script>
import {store} from "../store.js"

export default {
    name: `AppHeader`,

    data (){
    return{
      store
    }
  }
}

console.log(store.menu_voice)


</script>

<template>
  <h1>Header</h1>
</template>

<style>

</style>