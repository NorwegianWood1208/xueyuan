<template>
    <div class="herf-wrap">
        <div class="herf">
            <div class="title">友情链接</div>
            <div class="content">
                <div class="lis">
                    <img src="../../../assets/imgs/logo1.png" alt="">
                    <div class="des">友情链接</div>
                </div>
                <div class="lis">
                    <img src="../../../assets/imgs/logo1.png" alt="">
                    <div class="des">友情链接</div>
                </div>
                <div class="lis">
                    <img src="../../../assets/imgs/logo1.png" alt="">
                    <div class="des">友情链接</div>
                </div>
                <div class="lis">
                    <img src="../../../assets/imgs/logo1.png" alt="">
                    <div class="des">友情链接</div>
                </div>
                <div class="lis nomagin">
                    <img src="../../../assets/imgs/logo1.png" alt="">
                    <div class="des">友情链接</div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'IndexHerf'
}
</script>
<style lang="less" scoped>
    #app .nomagin{
        margin-right: 0px;
    }
    .herf-wrap{
        width: 100%;
        background: #fff;
        .herf{
            width: 1200px;
            height: 437px;
            margin: 0 auto;
            padding-top: 24px;
            .title{
                text-align: center;
                font: 36px/126px "黑体";
            }
            .content{
                width: 100%;
                height: 257px;
                .lis{
                    width: 180px;
                    height: 100%;
                    float: left;
                    margin-right: 75px;
                    img{
                        width: 180px;
                        height: 180px;
                    }
                    .des{
                        text-align: center;
                        font: 16px/76px "微软雅黑";
                    }
                }
            }
        }
    }
</style>
