<template>
    <div>
        <nav>
            <ul>
                <li>
                    <a href="">Home</a>
                </li>
                <li>
                    <a href="">Archives</a>
                </li>
                <li>
                    <a href="">Recent</a>
                </li>
                <li>
                    <a href="">Photo</a>
                </li>
                <li>
                    <a href="">About</a>
                </li>
                <li>
                    <a href="">Contact</a>
                </li>
            </ul>

        </nav>
        <div class="bottomBcg">

        </div>
    </div>
</template>

<script>
    export default {
        name: "Nav"
    }
</script>

<style scoped>
    *{
        margin: 0;
        padding: 0;
    }
    nav {
        width: 960px;
        height: 60px;
        margin: 0 auto;
        background: url("../../assets/images/templatemo_menu_panel_bg.jpg");
        background-size: 100% 100%;
        position: relative;
    }
    ul > li {
        width: 120px;
        height: 100%;
        list-style: none;
        float: left;
    }
    ul>li>a{
        display: block;
        width: 154px;
        text-decoration: none;
        color: white;
        text-align: center;
        line-height: 60px;
        font-size: 20px;
    }

    .bottomBcg{
        width: 960px;
        height: 250px;
        background: url("../../assets/images/templatemo_content_top.jpg");
        margin: 0 auto;
        z-index: -9999;
    }
</style>