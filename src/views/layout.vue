<template>
    <div class="layout-wrap">
        <div class="layout">
            <div class="title">
                Ecological layout
            </div>
            <div class="ul">
                <div class="lis">
                    <img src="../assets/imgs/切图/1.png" alt="">
                    <div class="lis-title">Lodging in high endexch-angel </div>
                    <div class="lis-des">New York Stock Echange NASDAQ Tokyo Stock Exchange</div>
                </div>
                <div class="lis">
                    <img src="../assets/imgs/切图/2.png" alt="">
                    <div class="lis-title">Lodging in high endexch-angel </div>
                    <div class="lis-des">New York Stock Echange NASDAQ Tokyo Stock Exchange</div>
                </div>
                <div class="lis">
                    <img src="../assets/imgs/切图/3.png" alt="">
                    <div class="lis-title">Lodging in high endexch-angel </div>
                    <div class="lis-des">New York Stock Echange NASDAQ Tokyo Stock Exchange</div>
                </div>
                <div class="lis nomargin">
                    <img src="../assets/imgs/切图/4.png" alt="">
                    <div class="lis-title">Lodging in high endexch-angel </div>
                    <div class="lis-des">New York Stock Echange NASDAQ Tokyo Stock Exchange</div>
                </div>
                <div class="lis">
                    <img src="../assets/imgs/切图/5.png" alt="">
                    <div class="lis-title">Lodging in high endexch-angel </div>
                    <div class="lis-des">New York Stock Echange NASDAQ Tokyo Stock Exchange</div>
                </div>
                <div class="lis">
                    <img src="../assets/imgs/切图/6.png" alt="">
                    <div class="lis-title">Lodging in high endexch-angel </div>
                    <div class="lis-des">New York Stock Echange NASDAQ Tokyo Stock Exchange</div>
                </div>
                <div class="lis">
                    <img src="../assets/imgs/切图/7.png" alt="">
                    <div class="lis-title">Lodging in high endexch-angel </div>
                    <div class="lis-des">New York Stock Echange NASDAQ Tokyo Stock Exchange</div>
                </div>
                <div class="lis nomargin">
                    <img src="../assets/imgs/切图/8.png" alt="">
                    <div class="lis-title">Lodging in high endexch-angel </div>
                    <div class="lis-des">New York Stock Echange NASDAQ Tokyo Stock Exchange</div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'IndexLayout'
}
</script>
<style lang="less" scoped>
    #app .nomagin{
        margin-right: 0
    }
    .layout-wrap{
        width: 100%;
        height: 1218px;
        background: #ffffff;
        .layout{
            width: 1500px;
            height: 1218px;
            padding-top: 12px;
            box-sizing: border-box;
            margin: 0 auto;
            .title{
                width: 100%;
                height: 182px;
                color: #000;
                font: 44px/182px "微软雅黑";
            }
            .ul{
                width: 100%;
                height: 990px;
                .lis{
                    width: 358px;
                    height: 412px;
                    float: left;
                    border: 2px solid #ebf0ff;
                    margin-right: 13px;
                    padding-top: 18px;
                    margin-bottom: 78px;
                    img{
                        margin-left: 22px;
                        margin-bottom: 28px;
                    }
                    .lis-title{
                        padding-left: 30px;
                        font: bold 22px/30px "微软雅黑";
                        margin-bottom: 16px;
                    }
                    .lis-des{
                        padding-left: 30px;
                        font: 20px/30px "微软雅黑";
                    }
                }
            }
        }
    }
</style>
