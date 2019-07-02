<template>
    <div class="app CompanyIntro">
        <div class="intro">
            <p>W3C Validations</p>
            <p class="introContent">Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus
                mus. Morbi dapibus dolor sit amet metus suscipit iaculis. </p>
            <div class="aW3C">
                <a href=""></a>
                <a href=""></a>
            </div>
        </div>
        <div class="intro">
            <p>Friends</p>
            <ul>
                <li>
                    <a href="">Website Templates</a>
                </li>
                <li>
                    <a href="">Flash Templates</a>
                </li>
                <li>
                    <a href="">Web Design Blog</a>
                </li>
                <li>
                    <a href="">Nunc blandit orci</a>
                </li>
                <li>
                    <a href="">Cum sociis natoque</a>
                </li>
            </ul>
        </div>
        <div class="intro">
            <p>Usage Policies</p>
            <ul>
                <li>
                    <a href="">Terms</a>
                </li>
                <li>
                    <a href="">Privacy</a>
                </li>
                <li>
                    <a href="">About</a>
                </li>
                <li>
                    <a href="">Contact</a>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
        name: "CompanyIntro"
    }
</script>

<style scoped>
    .CompanyIntro {
        display: flex;
        width: 900px;
        height: 206px;
        margin: 0 auto;
        background: url("../../assets/images/templatemo_content_bottom.jpg");
        background-size: 100% 100%;
    }

    .app > .intro {
        width: 305px;
        height: 200px;
        /*background: white;*/
        margin: 0 20px;
    }

    .intro > p:first-of-type {
        width: 272px;
        height: 28px;
        border-bottom: 1px dashed #663e17;
        font-size: 20px;
        color: #dbb4e0;
    }

    .intro > .introContent {
        color: wheat;
        margin: 20px 10px;
    }
    .intro>ul{
        list-style: none;
        margin: 20px 10px;
    }
    .intro>ul>li a{
        color: wheat;
        text-decoration: none;
    }
    .intro>ul>li::before{
        content: "+";
        color: wheat;
        margin-right: 5px;
    }
    .aW3C{
        display: flex;
        margin-left: 10px;
    }
    .aW3C >a{
        display: block;
        width: 88px;
        height: 31px;
    }
    .aW3C >a:first-of-type{
        background: url("../../assets/images/valid-xhtml10.png");
    }
    .aW3C >a:last-of-type{
        background: url("../../assets/images/vcss-blue.gif");
    }
</style>