<template>
    <div class="global-wrap">
        <div class="con-global">
            <h3 class="title"><span class="span1">Global</span> <span class="span2">trend</span></h3>
            <div class="ul1">
                <div class="ul">
                    <div class="lis ma-le-160">
                        <img src="../assets/imgs/切图/america.png" alt="">
                        <div class="lis-title">America</div>
                        <div class="lis-des">Commodity FuturesTrading Commission(CFTC) categorizes Bitcoin as “commodity”</div>
                    </div>
                    <div class="lis">
                        <img src="../assets/imgs/切图/singapore.png" alt="">
                        <div class="lis-title">Singapore</div>
                        <div class="lis-des">Singapore backs fiat Bitcoin with levies on trading</div>
                    </div>
                    <div class="lis">
                    <img src="../assets/imgs/切图/germany.png" alt="">
                        <div class="lis-title">Germany</div>
                        <div class="lis-des">Bitcoin has the equal status with fiat currency with cryptocurrency free of taxes.</div>
                    </div>
                    <div class="lis">
                        <img src="../assets/imgs/切图/canade.png" alt="">
                        <div class="lis-title">Canada</div>
                        <div class="lis-des">Canada acknowledges the legalization of trade of Bitcoin,which is ready to be included into governmental supervision and administration. </div>
                    </div>
                    <div class="lis">
                        <img src="../assets/imgs/切图/japan.png" alt="">
                        <div class="lis-title">Japan</div>
                        <div class="lis-des">Japan approves the regulatory law of digital currency  and defines Bitcoin as property.</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name:'IndexGlobal',
}
</script>
<style lang="less">
    #app .ma-le-160{
        margin-left: 160px;
    }
    .global-wrap{
        width: 100%;
        background: url(../assets/imgs/切图/clo背景.png) no-repeat;
        background-size: 100%;
        .con-global{
            width: 1500px;;
            height: 790px;
            margin: 0 auto;
            position: relative;
            padding-top: 175px;
            box-sizing: border-box;
            .title{
                width:590px;
                height: 42px;
                font: 42px/42px '微软雅黑';
                color: #000;
                position: absolute;
                top: 400px;
                left: -210px;
                text-align: right;
                transform: rotate(-90deg);
                .span1{
                    // color: #fff;
                }
                .span2{
                    margin-right: 20px;
                }
            }
            .ul1{
                overflow: hidden;
                .lis{
                    width: 230px;
                    height: 440px;
                    background: #fff;
                    margin-left: 37px;
                    padding-left: 30px;
                    padding-right: 30px;
                    padding-top: 22px;
                    float: left;
                    box-sizing: border-box;
                    img{
                        margin-left: 16px;
                        margin-bottom: 15px;
                    }
                    .lis-title{
                        width: 100%;
                        height: 30px;
                        text-align: center;
                        font:bold 16px/30px "微软雅黑";
                    }
                    .lis-des{
                        width: 100%;
                        font: 14px/24px "微软雅黑";
                        text-align:justify;
                        text-justify:inter-ideograph;
                        word-break:break-all;
                    }
                }
            }
        }
    }
</style>

