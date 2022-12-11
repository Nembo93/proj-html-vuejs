<script>
export default{
    name: `AppSectionSubject`
}
</script>

<template>
    <section class="section_subject">
        <div class="subject">
            <a href="" class="subject">
                <img src="../assets/h5-custom-icon-1.png" alt="">
                <h5>Languages</h5>
            </a>
        </div>

        <div class="subject">
            <a href="" class="subject">
                <img src="../assets/h5-custom-icon-2.png" alt="">
                <h5>Software</h5>
            </a>
        </div>

        <div class="subject">
            <a href="" class="subject">
                <img src="../assets/h5-custom-icon-3.png" alt="">
                <h5>Business</h5>
            </a>
        </div>

        <div class="subject">
            <a href="" class="subject">
                <img src="../assets/h5-custom-icon-4.png" alt="">
                <h5>Chemistry</h5>
            </a>
        </div>

        <div class="subject">
            <a href="" class="subject">
                <img src="../assets/h5-custom-icon-5.png" alt="">
                <h5>Science</h5>
            </a>
        </div>

        <div class="subject">
            <a href="" class="subject">
                <img src="../assets/h5-custom-icon-6.png" alt="">
                <h5>DIY&Craft</h5>
            </a>
        </div>
        
    </section>
</template>

<style>
.section_subject{
    display: flex;
    justify-content: space-between;
    padding-top: 30px;
    padding-bottom: 30px;
}
.subject{
    background-color: var(--secondary_color);
    width: auto;
    text-align: center;
    padding: 10px 20px;
}
.subject a{
    text-decoration: none;
}

.subject h5{
    color: black;
    margin-top: 20px;
}
.subject img{
    display: block;
}
</style>