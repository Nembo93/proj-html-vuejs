<script>
export default {
    name: `AppHeader`
}
</script>

<template>
  <section>
    <div class="container">
    
    <div class="disp_flex">
      <!-- col-1 -->
      <div class="foo_col">
        <div>
          <img class="foo_logo" src="../assets/logo-light.png" alt="">
        </div>
        
        <div>Providing Life Changing. Experience Through. Education. Class That Fit Your Busy Life. Closer to home</div>
        <div>1-677-124-44227</div>
        <div>Mon-Sat 8.00_18.00</div>
      </div>

      <!-- col-2 -->
      <div class="foo_col">
        <h4>Popular Courses</h4>
        <div>
          <span class="disp_block">Business English</span>
          <span class="disp_block">Preston Marshall</span>
        </div>
        <div>
          <span class="disp_block">Social Computing</span>
          <span class="disp_block">David Sanders</span>
        </div>
        <div>
          <span class="disp_block">Learn spanish</span>
          <span class="disp_block">Jennie King</span>
        </div>
      </div>

      <!-- col-3 -->
      <div class="foo_col">
        <h4>Support</h4>
        <div class="disp_flex flex_col">
          <a href="">User Dashboard</a>
          <a href="">Contact Us</a>
          <a href="">FAQ</a>
          <a href="">Course Offer</a>
          <a href="">Events</a>
        </div>
      </div>

      <!-- col-4 -->
      <div class="foo_col">
        <h4>Flexible Learning</h4>
        <div>
          <img class="foo_img" src="../assets/footer-img-1.png" alt="">
        </div>
      </div>
    </div>

    <hr class="foo_line">
    
    <div class="disp_flex space_bet">
      <div>Copyrights 2017@Mikado Themes</div>
      <div class="foo_contact">
        <span>CALL +44 300</span>
        <span>FOLLOW US</span>
        <span><i class="fa-brands fa-twitter"></i></span>
        <span><i class="fa-brands fa-instagram"></i></span>
        <span><i class="fa-brands fa-facebook-f"></i></span>
      </div>
    </div>

  </div>
  </section>
  
</template>

<style scoped>
section{
  background-color: black;
  color: white;
  padding-top: 100px;
  padding-bottom: 50px;
}
.foo_col{
  width: calc((100% / 5) * 1);
}
.foo_col{
  width: calc((100% / 5) * 2);
}
.foo_col div{
  margin-bottom: 20px;
}
.foo_col h4{
  margin-bottom: 20px;
}
.foo_img{
  width: 200px;
}
.foo_logo{
  width: 100px;
}
.foo_col a{
  text-decoration: none;
  margin-bottom: 20px;
  color: white;
  font-size: 12px;
}
.foo_line{
  color: white;
  margin-bottom: 50px;
}
.foo_contact span{
  font-size: 12px;
  margin-right: 15px;
}
</style>