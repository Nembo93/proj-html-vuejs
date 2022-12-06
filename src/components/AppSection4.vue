<script>
export default{
    name: `AppSection4`
}
</script>

<template>
    <section>
        <h1>Section 4</h1>
        <div class="disp_flex">
            <div class="deb_col">
                <div class="deb_box">What We Do</div>
                <div class="deb_box">Degree Programme</div>
                <div class="deb_box">Career Achievements</div>
                <div class="deb_box">Personal Management</div>
                <div class="deb_box">Step To Succes</div>
                <div class="deb_box">Knowledge Transfer</div>
            </div>

            <div class="deb_col">
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
.deb_col{
    width: 50%;
    height: 500px;
    border: 3px solid black;
    background-color: aqua;
}
.deb_box{
    height: calc(100% / 6);
    border: 1px solid black;
    background-color: blue;
}
</style>