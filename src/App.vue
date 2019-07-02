<template>
    <div id="app">
        <div style="width: 960px; margin: 0 auto;">
            <Header></Header>
            <Nav></Nav>
            <div class="content" style="display: flex;">
                <ContentLeft></ContentLeft>
                <ContentRight></ContentRight>
            </div>
        </div>
        <CompanyIntro></CompanyIntro>
        <div class="copy">
            <p>Copyright &copy; 2024 Your Blog Name | Designed by sc.chinaz.com</p>
        </div>
        <!--<p style="height: 100px;background: white;">-->
            <!--<i class="el-icon-edit"></i>-->
        <!--</p>-->
    </div>
</template>

<script>
    import Header from './components/Header'
    import Nav from './components/Nav'
    import ContentLeft from './components/ContentLeft'
    import ContentRight from './components/ContentRight'
    import CompanyIntro from './components/CompanyIntro'

    export default {
        name: 'app',
        components: {
            Header,
            Nav,
            ContentLeft,
            ContentRight,
            CompanyIntro
        }
    }
</script>

<style>
    * {
        margin: 0;
        padding: 0;
    }
    body{
        width: 100vw;
        height: 100%;
        background: #110915 fixed;
        background-size: 100% 100%;
        overflow:Scroll;
        overflow-x:hidden
    }
    .content{
        width: 960px;
        height: 885px;
        margin-top: -220px;
        /*margin-left: 214px;*/
        border-bottom: 1px solid #c3a3eb;
        margin-bottom: 43px;
    }
    .copy{
        width: 900px;
        height: 60px;
        background: url("assets/images/templatemo_footer_bg.jpg");
        margin: 0  auto;
    }
    .copy>p{
        text-align: center;
        line-height: 60px;
        color: white;
    }
</style>
