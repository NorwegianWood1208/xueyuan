<template>
    <div class="token-wrap">
        <div class="token">
            <div class="title">
                Token 
            </div>
            <div class="sanjiao">
                <img src="../assets/imgs/切图/TOKENTOP.png" alt="">
            </div>
            <div class="kuai">
                <div class="lis">
                    <img src="../assets/imgs/切图/超级节点.png" alt="">
                    <div class="kuai-title">Developers</div>
                </div>
                <div class="lis">
                    <img src="../assets/imgs/切图/开发者拷贝.png" alt="">
                    <div class="kuai-title">Community </div>
                </div>
                <div class="lis nomargin">
                    <img src="../assets/imgs/切图/社区鼠标滑过.png" alt="">
                    <div class="kuai-title">Super node</div>
                </div>
            </div>
            <div class="one">
                <div class="left">
                    <div class="left-title">300<span>millon </span>25%</div>
                    <div class="left-title1">NAIL Token Pre-sale Plan</div>
                    <div class="left-des">The project pre-sale plan is divided into three stages. The first phase, from July 25 to August 24, 2018, sold 60 million NAIL units at an advance price of 1.5 USDT. The second phase, from August 25 to October 15, 2018, pre-sold 90 million NAIL at a pre-sale price of 2 USDT. The second phase will be from October 15, 2018, to the start of the project, with a pre-sale of 150 million NAIL at a pre-sale price of 2.5 USDT.</div>
                </div>
                <img src="../assets/imgs/切图/sanpin.png" alt="">
            </div>
            <div class="two">
                <div class="left">
                    <div class="left-title">200<span>millon </span>20%</div>
                    <div class="left-title1">Unleashing Plan of the start-up</div>
                    <div class="left-des">The team release plan is divided into three stages. The first stage: January 2020, the total release of 100 million NAIL, accounting for 50%. The second stage: in January 2021, the total release of 50 million NAIL, accounting for 25%. The third stage: the time is January 2022, the total release is 50 million NAIL, accounting for 25%.</div>
                </div>
                <img src="../assets/imgs/切图/bingtu.png" alt="">
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'IndexToken'
}
</script>
<style lang="less" scoped>
    #app .nomargin{
        margin-right: 0px;
    }
    .token-wrap{
        width: 100%;
        background: #fff;
        .token{
            width: 1500px;
            // height: 1824px;
            margin:  0 auto;
            padding-top: 55px;
            box-sizing: border-box;
            .title{
                text-align: center;
                font: 30px/86px "微软雅黑";
            }
            .sanjiao{
                width: 100%;
                height: 96px;
                text-align: center;
            }
            .kuai{
                width: 100%;
                height: 250px;
                margin-bottom: 75px;
                .lis{
                    width: 421px;
                    height: 250px;
                    float: left;
                    margin-right: 115px;
                    border-radius: 10px;
                    border: 1px solid #cdcdcd;
                    img{
                        float: left;
                        margin: 60px 0 0 55px;
                    }
                    .kuai-title{
                        margin-top: 25%;
                        font: 30px/45px "微软雅黑";
                    }
                }
            }
            .one{
                width: 100%;
                height: 650px;
                .left{
                    width: 730px;
                    height: 650px;
                    float: left;
                    padding-top: 88px;
                    box-sizing: border-box;
                    .left-title{
                        color: #285aef;
                        font: 62px/118px "微软雅黑";
                        span{
                            color: #585b62;
                            margin-right: 30px;
                            font: 26px/26px "微软雅黑";
                        }
                    }
                    .left-title1{
                        font: 18px/66px "微软雅黑";
                    }
                    .left-des{
                        font: 16px/30px "微软雅黑";
                    }
                }
                img{
                    float: right;
                    margin-right: 158px;
                }
            }
            .two{
                width: 100%;
                height: 650px;
                .left{
                    width: 730px;
                    height: 650px;
                    float: right;
                    padding-top: 88px;
                    box-sizing: border-box;
                    .left-title{
                        color: #285aef;
                        font: 62px/118px "微软雅黑";
                        span{
                            color: #585b62;
                            margin-right: 30px;
                            font: 26px/26px "微软雅黑";
                        }
                    }
                    .left-title1{
                        font: 18px/66px "微软雅黑";
                    }
                    .left-des{
                        font: 16px/30px "微软雅黑";
                    }
                }
                img{
                    float: left;
                    margin-right: 158px;
                }
            }
        }
    }
</style>
