<script>
export default {
    name: `AppSection3`
}
</script>

<template>
    <section class="sec3">
        <div class="mg_auto txt_center">
            <img src="../assets/testimonials-standard-2.png" class="disp_block mg_auto" alt="">
            <p class="txt_center">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Laudantium distinctio tempore eum eligendi mollitia, odio sit soluta. Nostrum tempore a placeat voluptas ea tempora, atque deleniti, exercitationem, sint similique sapiente?</p>
            <span class="disp_block student_name">Joan Collins</span>
            <span class="disp_block">STUDENT</span>
        </div>
    </section>
</template>

<style scoped>
.sec3{
    background-image: url(../assets/interactive-map-slider-img-1.png);
    background-color: var(--primary_color);
    padding: 70px 70px;
    color: white;
}
.sec3 img, p{
    margin-bottom: 30px;
}
.student_name{
    font-size: 25px;
    margin-bottom: 10px;
}

</style>