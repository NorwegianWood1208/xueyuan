<template>
    <div class="core-wrap">
        <div class="core">
            <div class="title">区块链技术核心优势</div>
            <div class="content">
                <div class="lis">
                    <img class="img" src="../../../assets/imgs/logo1.png" alt="">
                    <div class="des">
                        去中心化的分布结构
                    </div>
                </div>
                <div class="lis">
                    <img class="img" src="../../../assets/imgs/logo2.png" alt="">
                    <div class="des">
                        不可篡改的时间戳
                    </div>
                </div>
                <div class="lis">
                    <img class="img" src="../../../assets/imgs/logo3.png" alt="">
                    <div class="des">
                        安全的信任机制
                    </div>
                </div>
                <div class="lis nomagin">
                    <img class="img" src="../../../assets/imgs/logo4.png" alt="">
                    <div class="des">
                        灵活的可编程特性
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'IndexCore',
}
</script>
<style lang="less" scoped>
    #app .nomagin{
        margin-right: 0px;
    }
    .core-wrap{
        width: 100%;
        height: 546px;
        .core{
            width: 1200px;
            height: 546px;
            margin: 0 auto;
            .title{
                width: 100%;
                height: 136px;
                text-align: center;
                font: 36px/136px "微软雅黑";
            }
            .content{
                width: 1200px;
                height: 300px;
                .lis{
                    width: 245px;
                    height: 300px;
                    float: left;
                    margin-right: 73px;
                    background: #fbfcff;
                    .img{
                        width: 88px;
                        height: 88px;
                        margin: 62px 0 33px 78px;
                    }
                    .des{
                        color: #4b75ff;
                        text-align: center;
                        font:bold 20px/34px "微软雅黑";
                    }
                }
            }
        }
    }
</style>
