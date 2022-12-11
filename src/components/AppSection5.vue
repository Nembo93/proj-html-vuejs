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
                    <div class="disp_flex space_bet">
                        <h4>Android developer</h4>
                        <div class="price_tag">FREE</div>
                    </div>
                    <span class="courses_teacher">David Sanders</span>
                    <p class="courses_info">Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus, aliquam voluptates sunt nam ipsam molestias assumenda facilis veritatis delectus ab doloribus nobis explicabo ad ullam excepturi recusandae. Magnam, atque explicabo.</p>
                    <span><i class="fa-solid fa-user"></i> 1 <i class="fa-solid fa-tag ml"></i> PROGRAMMING</span>
                </div>
            </div>

            <div class="sec5_card">
                <img src="../assets/process-img-1.png" class="disp_block" alt="">
                <div class="sec5_card_info">
                    <div class="disp_flex space_bet">
                        <h4>Web Designing</h4>
                        <div class="price_tag">FREE</div>
                    </div>
                    <span class="courses_teacher">Jennifer Powell</span>
                    <p class="courses_info">Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus, aliquam voluptates sunt nam ipsam molestias assumenda facilis veritatis delectus ab doloribus nobis explicabo ad ullam excepturi recusandae. Magnam, atque explicabo.</p>
                    <span><i class="fa-solid fa-user"></i> 1 <i class="fa-solid fa-tag ml"></i> PROGRAMMING</span>
                </div>
            </div>

            <div class="sec5_card">
                <img src="../assets/process-img-4.png" class="disp_block" alt="">
                <div class="sec5_card_info">
                    <div class="disp_flex space_bet">
                        <h4>Financial Modelling</h4>
                        <div class="price_tag">$20</div>
                    </div>
                    <span class="courses_teacher">Edward Bowmann</span>
                    <p class="courses_info">Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus, aliquam voluptates sunt nam ipsam molestias assumenda facilis veritatis delectus ab doloribus nobis explicabo ad ullam excepturi recusandae. Magnam, atque explicabo.</p>
                    <span><i class="fa-solid fa-user"></i> 1 <i class="fa-solid fa-tag ml"></i> BUSINESS</span>
                </div>
            </div>

        </div>


        
    </section>
    
</template>

<style scoped>
section{
    border-top: 1px solid lightgray;
    padding-top: 70px;
    padding-bottom: 70px;
    background-image: url(../assets/page-background-img.png);
}
h2{
    margin-bottom: 20px;
}
section > p{
    margin-bottom: 100px;
}
.sec5_card{
    border: 1px solid gray;
    width: calc((100% / 3) - 60px);
    color: gray;
}
.sec5_card_info{
    padding: 10px;
}
.sec5_card img{
    margin-bottom: 20px;
}

.courses_teacher{
    margin-top: 20px;
}
.courses_info{
    margin-top: 30px;
    margin-bottom: 30px;
}

.price_tag{
    border: 1px solid black;
    width: 60px;
    border-radius: 20px;
    padding: 3px 0px;
    font-size: 12px;
    text-align: center;
}
.ml{
    margin-left: 10px;
}
</style>