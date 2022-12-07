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
                <div class="sec4_box disp_flex">
                    <div class="hover_bar">
                        
                    </div>
                    <div>
                        <h3>What We Do</h3>
                    </div>
                </div>
                <div class="sec4_box">
                    <h4>Degree Programme</h4>
                </div>
                <div class="sec4_box">
                    <h4>Career Achievements</h4>
                </div>
                <div class="sec4_box">
                    <h4>Personal Management</h4>
                </div>
                <div class="sec4_box">
                    <h4>Step To Succes</h4>
                </div>
                <div class="sec4_box">
                    <h4>Knowledge Transfer</h4>
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

                    <div>
                        <img src="../assets/h12-tabs-icon-1.png" alt="">
                    </div>
                </div>
                
            </div>
        </div>
    </section>

</template>

<style scoped>
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


.hover_bar{
    width: 10px;
    background-color: aqua;
    margin-right: 20px;
}
</style>