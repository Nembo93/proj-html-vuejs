<script>
import {store} from "../store.js"

export default {
    name: `AppHeader`,

    data (){
    return{
      store,
    }
  },
  
}

console.log(store.menu_voice)


</script>

<template>
  <header class="header_app_head">
    <div class="header_bar">
      <div class="header_bar_left">
        <img src="../assets/logo-light.png" alt="">
      </div>

      <div class="header_bar_middle">
        <a href="" v-for="voice in store.menu_voice">{{voice}}</a>
      </div>

      <div class="header_bar_right">
        <div><i class="fa-solid fa-magnifying-glass"></i></div>
        <div><i class="fa-solid fa-briefcase"></i></div>
        <div><i class="fa-solid fa-bars"></i></div>
      </div>
    </div>

  <div class="header_core">
    <h1>Contemporary Ideas</h1>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Expedita vitae consectetur aperiam corporis molestias nemo alias accusantium sint assumenda eveniet voluptatum eligendi reiciendis, dolore doloribus ex officiis, laborum amet nostrum!</p>
    <a class="header_button" href="">REGISTER NOW</a>
  </div>

  <div>
    <input type="radio" name="header_scroll" class="header_scroll_btn">
    <input type="radio" name="header_scroll" class="header_scroll_btn">
    <input type="radio" name="header_scroll" class="header_scroll_btn">
  </div>
  </header>
  
</template>

<style scoped>
.header_app_head{
  background-image: url(../assets/h5-slide-3-background.jpg);
  background-size: 100%;
}
.header_core{
  text-align: center;
  padding-top: 100px;
  padding-left: 200px;
  padding-right: 200px;
  padding-bottom: 200px;
  color: white;
}

.header_core p{
  margin-top: 30px;
  margin-bottom: 80px;
}
.header_button{
  text-decoration: none;
  color: white;
  background-color: var(--primary_color);
  padding: 20px 30px;
  margin-bottom: 100px;
}
.header_bar{
  display: flex;
  padding-top: 30px;
}
.header_bar div{
  color: white;
}
.header_bar_left{
  width: 20%;
  align-items: center;
}
.header_bar_left img{
  max-width: 60%;
  display: block;
  margin: auto;
}
.header_bar_middle{
  width: 65%;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
.header_bar_middle a{
  text-decoration: none;
  color: white;
}
.header_bar_right{
  width: 15%;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
.header_bar_right i{
  font-size: 20px;
}
</style>