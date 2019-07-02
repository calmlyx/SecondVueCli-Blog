<template>
    <div class="app">
        <div class="contentR">
            <p>About This Blog</p>
            <p>This free web blog layout is provided by TemplateMo.com. You may download, modify and apply this layout
                for any blog CMS websites.</p>
        </div>
        <div class="contentR">
            <p>Categories</p>
            <ul>
                <li><a href="">Lorem ipsum</a></li>
                <li><a href="">Duis mollis</a></li>
                <li><a href="">Maecenas adipiscing</a></li>
                <li><a href="">Nunc blandit orci</a></li>
                <li><a href="">Cum sociis natoque</a></li>
            </ul>
        </div>
        <div class="contentR">
            <p>Archives</p>
            <ul>
                <li><a href="">January 2024</a></li>
                <li><a href="">December 2023</a></li>
                <li><a href="">November 2023</a></li>
                <li><a href="">October 2023</a></li>
                <li><a href="">September 2023</a></li>
            </ul>
        </div>
        <div class="contentR">
            <p>Recent Comments</p>
            <ul>
                <li>Lorem Ipsum on Donec </li>
                <li>Consectetuer on Suspendisse </li>
                <li>Sed on Pellentesque</li>
                <li>Vitae Neque on Nunc</li>
                <li>Donec Mollis on Maecenas</li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
        name: "ContentRight"
    }
</script>

<style scoped>
    .app {
        width: 310px;
        height: 872px;
        color: white;
    }

    .app > .contentR {
        width: 280px;
        height: 185px;
        background: url("../../assets/images/templatemo_right_section_bg.jpg");
        background-size: 100% 100%;
        margin: 32px auto;
    }

    .app > .contentR:first-child {
        margin-top: 0;
    }

    .app > .contentR:last-child {
        margin-bottom: 0;
    }
    .app > .contentR > p:first-child {
        width: 250px;
        height: 42px;
        border-bottom: 1px dashed #663e17;
        margin: 0 auto;
        font-size: 25px;
        line-height: 42px;
        margin-bottom: 20px;
    }
    .app > .contentR>p:last-child{
        width: 250px;
        margin: 0px auto;
        line-height: 20px;
    }

    .contentR > ul {
        width: 250px;
        margin: 0px auto;
    }

    .contentR > ul > li {
        font-size: 12px;
        list-style: none;
        margin: 6px auto;
    }
    .contentR > ul > li::before {
       content: ">";
        margin-right: 5px;
        color: cornflowerblue;
    }

    .contentR > ul > li > a {
        color: #d3c2f9;
        text-decoration: none;
        font-size: 12px;
    }

    .contentR > ul > li > a:hover {
        color: #ffb809;
    }
</style>