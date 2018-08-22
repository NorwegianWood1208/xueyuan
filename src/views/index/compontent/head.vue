<template>
    <div class="wrap-head">
        <div class="head">
            <h1 class="logo">深创学院</h1>
            <div class="nav">
                <div class="lis">首页</div>
                <div class="lis">报刊</div>
                <div class="lis">专访沙龙</div>
                <div class="lis">经济快讯</div>
                <div class="lis">关于我们</div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'IndexHead'
}
</script>
<style lang="less" scoped>
    .wrap-head{
        width: 100%;
        background: #282730;
        .head{
            width: 1200px;
            height: 80px;
            margin:  0 auto;
            
            .logo{
                float: left;
                color: #476deb;
                font: 24px/80px "微软雅黑";
                margin-left: 34px;
            }
            .nav{   
                overflow: hidden;
                color: #fff;
                float: right;
                font: 16px/78px "微软雅黑";
                .lis:hover{
                    cursor: pointer;
                    border-top: 2px solid #476deb;
                }
                .lis{
                    float: left;
                    padding: 0 26px;
                }
            }
        }
    }
</style>
