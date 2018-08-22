<template>
    <div class="foot-wrap">
        <div class="foot">
            <div class="title">关于我们</div>
            <div class="content">
                <div class="left">
                    <div class="lis">公司地址：北京市大兴区深创学院</div>
                    <div class="lis">联系电话：18500892223</div>
                    <div class="lis">备案号：4564564564</div>
                </div>
                <div class="right">
                    <div class="lis">
                        <img src="../../../assets/imgs/erweima.png" alt="">
                        <div class="des">商务合作</div>
                    </div>
                    <div class="lis magin-le53">
                        <img src="../../../assets/imgs/erweima.png" alt="">
                        <div class="des">微信合作</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'IndexFoot'
}
</script>
<style lang="less" scoped>
    #app .magin-le53{
        margin-left: 53px;
    }
    .foot-wrap{
        width: 100%;
        // height: 322px;
        background: #282730;
        .foot{
            width: 1200px;
            height: 322px;
            margin:  0 auto;
            .title{
                color: #fff;
                font: 18px/115px "微软雅黑";
                border-bottom:1px solid #42414f;
            }
            .content{
                width: 100%;
                height: 207px;
                padding-top: 18px;
                box-sizing: border-box;
                .left{
                    width: 622px;
                    height: 100%;
                    float: left;
                    color: #edf1ff;
                    font: 16px/56px "微软雅黑";
                }
                .right{
                    width: 562px;
                    height: 100%;
                    float: left;
                    .lis{
                        width: 108px;
                        height: 170px;
                        float: left;
                        margin-left: 240px;
                        .des{
                            color: #fff;
                            text-align: center;
                            font:16px/60px "微软雅黑";
                        }
                    }
                }
            }
        }
    }
</style>
