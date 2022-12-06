<script>
export default{
    name: `AppSection4`
}
</script>

<template>
    <section>
        <h1>Section 4</h1>
        <div class="disp_flex">
            <div class="sec4_col">
                <div class="sec4_box">What We Do</div>
                <div class="sec4_box">Degree Programme</div>
                <div class="sec4_box">Career Achievements</div>
                <div class="sec4_box">Personal Management</div>
                <div class="sec4_box">Step To Succes</div>
                <div class="sec4_box">Knowledge Transfer</div>
            </div>

            <div class="sec4_col">
                <h2>Learning possibilities</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dicta fugit accusantium saepe quasi similique vitae reiciendis nemo delectus doloremque quibusdam labore natus officiis illum libero, praesentium provident in modi! Molestiae?</p>

                <span class="disp_block"><i class="fa-solid fa-check"></i>We enrich lives through learning.</span>
                <span class="disp_block"><i class="fa-solid fa-check"></i>Maximizin potential through individual attention.</span>
                <span class="disp_block"><i class="fa-solid fa-check"></i>The trusted name for specialized Training.</span>
                <span class="disp_block"><i class="fa-solid fa-check"></i>People teach. Peaople learn. This is where their connect.</span>
            </div>
        </div>
    </section>

</template>

<style>
.sec4_col{
    width: 50%;
    height: 500px;
    border: 3px solid black;
    background-color: aqua;
}
.sec4_box{
    height: calc(100% / 6);
    border: 1px solid black;
    background-color: blue;
}
</style>