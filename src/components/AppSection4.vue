<script>
export default{
    name: `AppSection4`
}
</script>

<template>
    <section>
        <h1>Section 4</h1>
        <div class="disp_flex">
            <div class="sec4_col sec4_col_left">

                <div class="sec4_box disp_flex sec4box1">
                    <div class="hover_bar1">
                        
                    </div>
                    <div>
                        <h3>What We Do</h3>
                    </div>
                </div>

                <div class="sec4_box disp_flex sec4box2">
                    <div class="hover_bar2">
                        
                    </div>
                    <div>
                        <h3>Degree Programme</h3>
                    </div>
                </div>

                <div class="sec4_box disp_flex sec4box3">
                    <div class="hover_bar3">
                        
                    </div>
                    <div>
                        <h3>Career Achievementso</h3>
                    </div>
                </div>

                <div class="sec4_box disp_flex sec4box4">
                    <div class="hover_bar4">
                        
                    </div>
                    <div>
                        <h3>Personal Management</h3>
                    </div>
                </div>

                <div class="sec4_box disp_flex sec4box5">
                    <div class="hover_bar5">
                        
                    </div>
                    <div>
                        <h3>Step To Succes</h3>
                    </div>
                </div>

                <div class="sec4_box disp_flex sec4box6">
                    <div class="hover_bar6">
                        
                    </div>
                    <div>
                        <h3>Knowledge Transfer</h3>
                    </div>
                </div>
                
            </div>

            <div class="sec4_col sec4_col_right">
                <h2>Learning possibilities</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dicta fugit accusantium saepe quasi similique vitae reiciendis nemo delectus doloremque quibusdam labore natus officiis illum libero, praesentium provident in modi! Molestiae?</p>

                <div class="disp_flex">
                    <div>
                        <span class="disp_block"><i class="fa-solid fa-check"></i>We enrich lives through learning.</span>
                        <span class="disp_block"><i class="fa-solid fa-check"></i>Maximizin potential through individual attention.</span>
                        <span class="disp_block"><i class="fa-solid fa-check"></i>The trusted name for specialized Training.</span>
                        <span class="disp_block"><i class="fa-solid fa-check"></i>People teach. Peaople learn. This is where their connect.</span>
                    </div>

                    <div class="col_right_img">
                        <img src="../assets/h12-tabs-icon-1.png" alt="">
                    </div>
                </div>
                
            </div>
        </div>
    </section>

</template>

<style scoped>
*{
    color: gray;
}
.sec4_col{
    height: 500px;
    border: 3px solid black;
}
.sec4_col_left{
    width: 30%;
}
.sec4_col_right{
    width: 70%;
    padding-left: 20px;
}
.sec4_col_right h2{
    margin-top: 20px;
    margin-bottom: 50px;
}
.sec4_col_right p{
    margin-bottom: 70px;
}
.sec4_col_right span{
    font-size: 20px;
    margin-bottom: 20px;
}
.sec4_col_right i{
    color: green;
    margin-right: 10px;
}
.sec4_box{
    height: calc(100% / 6);
    border: 1px solid black;
}
.sec4_col_right img{
    width: 150px;
}
.col_right_img{
    padding: 20px;
}


.sec4box1:hover .hover_bar1{
    display: block;
    color: aqua;
}
.hover_bar1{
    width: 10px;
    background-color: aqua;
    margin-right: 20px;
    display: none;
}

.sec4box2:hover .hover_bar2{
    display: block;
}
.hover_bar2{
    width: 10px;
    background-color: aqua;
    margin-right: 20px;
    display: none;
}

.sec4box3:hover .hover_bar3{
    display: block;
}
.hover_bar3{
    width: 10px;
    background-color: aqua;
    margin-right: 20px;
    display: none;
}

.sec4box4:hover .hover_bar4{
    display: block;
}
.hover_bar4{
    width: 10px;
    background-color: aqua;
    margin-right: 20px;
    display: none;
}

.sec4box5:hover .hover_bar5{
    display: block;
}
.hover_bar5{
    width: 10px;
    background-color: aqua;
    margin-right: 20px;
    display: none;
}

.sec4box6:hover .hover_bar6{
    display: block;
}
.hover_bar6{
    width: 10px;
    background-color: aqua;
    margin-right: 20px;
    display: none;
}
</style>