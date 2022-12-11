<script>
export default{
    name: `AppSection1`
}
</script>

<template>
    <section class="sec1">
        <h2>The Trusted Name <br> for In-Home Tutoring.</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum fugit velit qui deserunt modi. Aliquid id repellat exercitationem nemo saepe alias, dolore unde natus quaerat repellendus fugiat assumenda, adipisci maxime.</p>
        <a href="">LEARN MORE</a>
        <img class="sec1_img" src="../assets/h1-slide-3-background.jpg" alt="">
    </section>
</template>

<style scoped>
a{
    text-decoration: none;
    color: var(--primary_color);
}

.sec1 h2, p, a{
    margin-bottom: 20px;
}
.sec1_img{
    margin-top: 100px;
    max-width: 1200px;
}
.sec1{
    padding-bottom: 100px;
}
</style>