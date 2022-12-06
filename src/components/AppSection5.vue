<script>
export default{
    name: `AppSection5`
}
</script>

<template>
    <section>
        <h2 class="txt_center">Popular Online Courses</h2>
        <p class="txt_center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit, dolorem? Adipisci provident aliquid deserunt! Esse ab eveniet necessitatibus perspiciatis impedit dicta, nihil vitae sint! Error cupiditate sint facere impedit itaque.</p>

        <div class="disp_flex space_bet">

            <div class="sec5_card">
                <img src="../assets/process-img-3.png" class="disp_block" alt="">
                <div class="sec5_card_info">
                    <h4>Android developer</h4>
                    <span>David Sanders</span>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus, aliquam voluptates sunt nam ipsam molestias assumenda facilis veritatis delectus ab doloribus nobis explicabo ad ullam excepturi recusandae. Magnam, atque explicabo.</p>
                    <span><i class="fa-solid fa-user"></i> 1 <i class="fa-solid fa-tag"></i> PROGRAMMING</span>
                </div>
            </div>

            <div class="sec5_card">
                <img src="../assets/process-img-3.png" class="disp_block" alt="">
                <div class="sec5_card_info">
                    <h4>Android developer</h4>
                    <span>David Sanders</span>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus, aliquam voluptates sunt nam ipsam molestias assumenda facilis veritatis delectus ab doloribus nobis explicabo ad ullam excepturi recusandae. Magnam, atque explicabo.</p>
                    <span><i class="fa-solid fa-user"></i> 1 <i class="fa-solid fa-tag"></i> PROGRAMMING</span>
                </div>
            </div>

            <div class="sec5_card">
                <img src="../assets/process-img-3.png" class="disp_block" alt="">
                <div class="sec5_card_info">
                    <h4>Android developer</h4>
                    <span>David Sanders</span>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus, aliquam voluptates sunt nam ipsam molestias assumenda facilis veritatis delectus ab doloribus nobis explicabo ad ullam excepturi recusandae. Magnam, atque explicabo.</p>
                    <span><i class="fa-solid fa-user"></i> 1 <i class="fa-solid fa-tag"></i> PROGRAMMING</span>
                </div>
            </div>

        </div>


        
    </section>
    
</template>

<style>
.sec5_card{
    border: 1px solid gray;
    width: calc((100% / 3) - 60px);
}
.sec5_card_info{
    padding: 10px;
}
</style>