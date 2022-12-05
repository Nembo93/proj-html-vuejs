<script>
import {store} from "../store.js"

export default {
    name: `AppHeader`,

    data (){
    return{
      store
    }
  },

  methods:{
    function () {	
		voice = voice.toUpperCase();
    }
   }
}

console.log(store.menu_voice)


</script>

<template>
  <div class="header_bar">
    <div class="header_bar_left">left</div>
    <div class="header_bar_middle">
      <a href="" v-for="voice in store.menu_voice">{{voice}}</a>
    </div>
    <div class="header_bar_right">right</div>
  </div>
</template>

<style>
.header_bar{
  display: flex;
}
.header_bar div{
  border: 1px solid black;
}
.header_bar_left{
  width: 30%;
}
.header_bar_middle{
  width: 50%;
  display: flex;
  justify-content: space-around;
}
.header_bar_middle a{
  text-decoration: none;
}
.header_bar_right{
  width: 20%;
}

</style>