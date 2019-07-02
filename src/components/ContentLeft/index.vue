<template>
    <div class="app">
        <div class="appUp">
            <p>Recent Photos</p>
            <div class="imgBanner">
                <el-carousel :interval="5000" arrow="always" style="height: 250px; overflow: hidden;">
                    <el-carousel-item v-for="(img,index) in imgList" :key="index" style="height: 250px;">
                        <img v-bind:src="img.url">
                    </el-carousel-item>
                </el-carousel>
            </div>
        </div>
        <div class="appDown">
            <div class="header">
                <p>Blog post title goes here</p>
                <p>Posted by TemplateMo,January 31,2024 at 11:12 AM,in Player</p>
            </div>
            <div class="bottom">
                <img src="../../assets/images/templatemo_image_1.jpg" width="510" height="165">
                <div class="footer">
                    <p>Credits go to bittbox.com for the texture and SawII for photos.</p>
                    <p>Fusce non lacus et lorem ornare interdum. Nunc eget urna. Mauris vestibulum felis eget tortor. Praesent mattis varius quam. Vestibulum ullamcorper ipsum nec augue. Vestibulum auctor odio eget ante.</p>
                    <p>Nunc commodo, magna pharetra semper vehicula, dui ligula feugiat elit, et euismod nunc orci ut libero. Etiam sodales massa vel metus. Mauris et elit quis mauris aliquet luctus.</p>
                </div>
                <a href="">No comment</a>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "ContentLeft",
        data(){
            return{
                imgList:[
                    {url:require('../../assets/images/templatemo_image_2.jpg')},
                    {url:require('../../assets/images/templatemo_image_3.jpg')},
                    {url:require('../../assets/images/templatemo_image_4.jpg')}
                ]
            }
        }
    }
</script>

<style scoped>
    .app {
        width: 625px;
        height: 872px;
    }

    .appUp {
        width: 602px;
        height: 292px;
        margin: 0 auto;
        background: rgb(24,13,30);
    }

    .appUp p:nth-of-type(1) {
        height: 40px;
        font-size: 30px;
        color: #dbb4e0;
    }

    .imgBanner {
        width: 100%;
        height: 215px;
    }
    .bannerHao>ul{
        list-style: none;
        margin-top: 10px;
    }
    .bannerHao>ul>li{
        float: left;
        width: 15px;
        height: 20px;
        margin-left: 5px;
        line-height: 20px;
        background: #4e305f;
        text-align: center;
        color: white;
    }
    /*.........*/

    .appDown {
        width: 602px;
        height: 470px;
        margin: 0 auto;
        margin-top: 30px;
    }
    .bottom{
        height: 400px;
        background: rgb(24,13,30);
        padding-top : 5px;
        padding-bottom: 30px;
    }
    .appDown>.header {
        width: 100%;
        height: 75px;
        background: url("../../assets/images/templatemo_post_title_bg.jpg");
    }
    .appDown>.header>p {
        margin-left: 50px;
    }
    .bottom>.footer {
        margin-top: 20px;
         margin-left: 50px;
     }
    .bottom>.footer>p {
        margin-top: 15px;
        color: wheat;
    }
    .appDown>.header p:first-of-type {
        font-size: 30px;
        color: white;
    }
    .appDown>.header p:last-of-type {
        color: #dbb4e0;
    }

    .bottom > img {
        display: block;
        margin-left: 50px;
        margin-top: 20px;
    }
    .bottom>a{
        display: block;
        margin-top: 20px;
        margin-left: 50px;
        color: #dbb4e0;
        text-decoration: none;
        font-weight: bold;
        font-size: 18px;
    }
    .el-carousel__item h3 {
        color: #475669;
        font-size: 18px;
        opacity: 0.75;
        /*line-height: 300px;*/
        margin: 0;
    }
</style>