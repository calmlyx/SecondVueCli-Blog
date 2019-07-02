<template>
    <div class="search">
        <div class="logo">
            WEB BLOG
        </div>
        <div class="searchForm">
            <form action="">
                <input type="radio" name="searchR" checked id="thisSite" class="searchR"> <label for="thisSite">this Site</label>
                <input type="radio" name="searchR" id="theWeb" class="searchR"><label for="theWeb"> the Web</label><br>
                <input type="text"><button>search</button>
            </form>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>
    *{
        color: white;
    }
    .search {
        width: 960px;
        height: 145px;
        position: relative;
        background: url("../../assets/images/templatemo_top_panel_bg.jpg");
        margin: 0 auto;
        /*border: 1px solid white;*/
    }
    .search>.logo{
        font-size: 50px;
        color: #d3c2f9;
        line-height: 145px;
        margin: 0 20px;
    }
    .search>.searchForm{
        position: absolute;
        right: 40px;
        top: 65px;
    }
    .search>.searchForm form label{
        margin-right: 10px;
    }
    form>input[type="radio"]{
        margin-bottom: 10px;
    }
    form>input[type="text"]{
        width: 240px;
        height: 25px;
        background: none;
        border: 1px solid #874d76;
    }
    form>button{
        width: 66px;
        height: 25px;
        margin-left: 10px;
        color: #000;
    }
</style>