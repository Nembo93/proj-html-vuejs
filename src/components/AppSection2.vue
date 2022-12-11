<script>
export default{
    name: `AppSection2` 
}
</script>

<template>
    <section>
        <div class="section_2" >
            <div class="box_section_2">
                <img class="sec2_img disp_block" src="../assets/h8-slide-1-img.png" alt="">
            </div>
            <div class="box_section_2">
                <h2>Empowering Children to reach their potential</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iusto, odio deserunt aliquid ad natus beatae? Magnam dolorem consequuntur incidunt in recusandae eaque accusantium? Eveniet deleniti molestiae laudantium, quod quaerat voluptatibus.</p>
                
                <div class="disp_flex">
                    <div class="sec2_args_box">
                        <span class="sec2_count disp_block">168</span>
                        <span class="sec2_args">User Stories</span>
                    </div>
                    <div class="sec2_args_box">
                        <span class="sec2_count disp_block">347</span>
                        <span class="sec2_args" >Events</span>
                    </div>
                </div>
            </div>
        </div>

        


        
    </section>
</template>

<style scoped>
section{
    padding-bottom: 50px;
}
.section_2{
    display: flex;
}
.box_section_2 > h2, p{
    margin-bottom: 50px;
    text-align: left;
    padding-right: 50px;
}
.box_section_2{
    width: 50%;
}
.box_section_2 h2{
    margin-top: 30px;
}
.sec2_img{
    max-width: 350px;
    margin: auto;
}
.sec2_count{
    font-size: 50px;
    color: var(--primary_color);
}
.sec2_args{
    font-size: 30px;
    color: var(--primary_color);
}
.sec2_args_box{
    width: 50%;
}
.box_section_2 > span{
    text-align: left;
    padding-right: 50px;
}
</style>