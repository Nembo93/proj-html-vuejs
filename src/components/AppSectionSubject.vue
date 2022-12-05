<script>
export default{
    name: `AppSectionSubject`
}
</script>

<template>
    <section>
        <div class="subject">
            <a href="" class="subject">
                <img src="../assets/h5-custom-icon-1.png" alt="">
                <h5>Languages</h5>
            </a>
        </div>

        <div class="subject">
            <a href="" class="subject">
                <img src="../assets/h5-custom-icon-1.png" alt="">
                <h5>Software</h5>
            </a>
        </div>

        <div class="subject">
            <a href="" class="subject">
                <img src="../assets/h5-custom-icon-1.png" alt="">
                <h5>Business</h5>
            </a>
        </div>

        <div class="subject">
            <a href="" class="subject">
                <img src="../assets/h5-custom-icon-1.png" alt="">
                <h5>Chemistry</h5>
            </a>
        </div>

        <div class="subject">
            <a href="" class="subject">
                <img src="../assets/h5-custom-icon-1.png" alt="">
                <h5>Science</h5>
            </a>
        </div>

        <div class="subject">
            <a href="" class="subject">
                <img src="../assets/h5-custom-icon-1.png" alt="">
                <h5>DIY&Craft</h5>
            </a>
        </div>
        
    </section>
</template>

<style>
section{
    display: flex;
    justify-content: space-between;
    padding-top: 30px;
    padding-bottom: 30px;
}
.subject{
    background-color: lightblue;
    width: auto;
    text-align: center;
    padding: 20px 10px;
}
.subject a{
    text-decoration: none;
}
/* .subject img{
    margin-bottom: 10px;
} */
.subject h5{
    color: black;
}
</style>