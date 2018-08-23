<template>
    <div class="img-wrap">
        <div class="img">
            <div class="left">
                <div class="lis"><span>√</span> national blockchain landmarks</div>
                <div class="lis"><span>√</span> Recognition by 20 sovereignty countries</div>
                <div class="lis"><span>√</span> NAIL  Powerful ecological hatching</div>
                <div class="lis"><span>√</span> Trading in national exchange</div>
                <div class="lis"><span>√</span> NAIL  Business institution</div>
                <div class="lis"><span>√</span> NAILExchange center for countries</div>
            </div>
            <div class="right">
                <img class="logo1" src="../assets/imgs/切图/STRJIAO.png" alt="">
                <div class="title">
                    Strategic objectives
                </div>
                <img class="logo2" src="../assets/imgs/切图/logo.png" alt="">
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'IndexImg'
}
</script>
<style lang="less" scoped>
    .img-wrap{
        width: 100%;
        height: 440px;
        background: url(../assets/imgs/切图/token背景.png) no-repeat;
        background-size: 100%;
        .img{
            width: 1500px;
            height: 440px;
            margin: 0 auto;
            .left{
                width: 700px;
                height: 440px;
                float: left;
                box-sizing: border-box;
                padding-top: 70px;
                .lis{
                    color: #fff;
                    font: 18px/48px "微软雅黑";
                    span{
                        margin-right: 34px;
                    }
                }
            }
            .right{
                width: 800px;
                height: 440px;
                float: right;
                padding-top: 48px;
                box-sizing: border-box;
                .logo1{
                    float: right;
                }
                .title{
                    color: #fff;
                    margin-top: 70px;
                    text-align: center;
                    font:bold 36px/76px "微软雅黑";
                }
                .logo2{
                    width: 220px;
                    height: 60px;
                    margin-left: 270px;
                }
            }
        }
    }
</style>
