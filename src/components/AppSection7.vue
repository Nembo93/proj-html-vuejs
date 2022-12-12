<script>
export default{
    name: `AppSection7`
}
</script>

<template>
    <section>
        <div class="disp_flex space_bet">
            <div>
                <img src="../assets/h5-client-5.png" alt="">
            </div>
            <div>
                <img src="../assets/h5-client-1.png" alt="">
            </div>
            <div>
                <img src="../assets/h5-client-2.png" alt="">
            </div>
            <div>
                <img src="../assets/h5-client-1.png" alt="">
            </div>
        </div>

        <button class="my_scroll_button my_scroll_button6">
            <i class="fa-solid fa-chevron-up"></i>
            TOP
        </button>

    </section>
</template>

<style scoped>
section{
    border-top: 1px solid lightgray;
    padding-top: 70px;
    padding-bottom: 70px;
    position: relative;
}
.my_scroll_button{
    position: absolute;
    right: 0%;
    top: 5%;
}
</style>