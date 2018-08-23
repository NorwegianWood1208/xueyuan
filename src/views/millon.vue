<template>
    <div class="millon-wrap">
        <div class="millon">
            <div class="left">
                <div class="title">300<span>millon</span></div>
                <div class="des">NAIL is a bottom system which can achieve smartcontraction on blockchain with constant aggregate circulation of 1 billion and without future additional increasing.</div>
            </div>
            <div class="right">
                <div class="lis">
                    <div class="title">20%</div>
                    <div class="des">Start-up</div>
                </div>
                <div class="lis nomagin-r">
                    <div class="title">30%</div>
                    <div class="des">Pre-sale</div>
                </div>
                <div class="lis nomagin-b">
                    <div class="title">30%</div>
                    <div class="des">Brand operation</div>
                </div>
                <div class="lis  nomagin-b nomagin-r">
                    <div class="title">20%</div>
                    <div class="des">Foundation</div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'IndexMillon'
}
</script>
<style lang="less" scoped>
    #app .nomagin-r{
        margin-right: 0px;
    }
    #app .nomagin-b{
        margin-bottom: 0px;
    }
    .millon-wrap{
        width: 100%;
        height: 672px;
        background: url(../assets/imgs/切图/token背景.png) no-repeat;
        background-size:100%; 
        .millon{
            width: 1500px;
            overflow: hidden;
            margin: 0 auto;
            padding-top: 182px;
            .left{
                width: 620px;
                height: 468px;
                float: left;
                .title{
                    color: #fff;
                    font: 60px/130px "微软雅黑";
                    span{
                        font: 28px/28px "微软雅黑";
                    }
                }
                .des{
                    color: #fff;
                    font: 18px/46px "微软雅黑";
                }
            }
            .right{
                width: 830px;
                overflow: hidden;
                float: right;
                .lis{
                    height: 155px;
                    width: 394px;;
                    float: left;
                    color: #fff;
                    box-sizing: border-box;
                    padding-top: 20px;
                    padding-left: 40px;
                    margin-bottom: 54px;
                    margin-right: 33px;
                    border-radius: 20px;
                    background: #295af2;
                    .title{
                        font: 34px/58px "微软雅黑";
                    }
                    .des{
                        font: 22px/42px "微软雅黑";
                    }
                }
            }
        }
    }
</style>
