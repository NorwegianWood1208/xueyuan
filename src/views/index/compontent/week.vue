<template>
    <div class="week-wrap">
        <div class="week">
            <div class="title">区块链周刊</div>
            <div class="content">
                <div class="word">
                    <div class="word-title">第二期</div>
                    <div class="time">2018.10.13  15:30</div>
                    <div class="des">
                        介绍：开了房哈司法所开发和康师傅和康师傅看看是否哈萨克付货款是凤凰卡刷卡复活卡是否好看撒好看
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'IndexWeek'
}
</script>
<style lang="less" scoped>
    .week-wrap{
        width: 100%;
        background: #f5f7ff;
        .week{
            width: 1204px;
            height: 654px;
            margin: 0 auto;
            padding-top: 60px;
            box-sizing: border-box;
            padding-top: 12px;
            .title{
                text-align: center;     
                font: 36px/122px "黑体";
            }
            .content{
                width: 100%;
                height: 520px;
                background:#fff url(../../../assets/imgs/pic1.png) no-repeat;
                .word{
                    width: 405px;
                    height: 520px;
                    float: right;
                    padding-top: 66px;
                    padding-left: 57px;
                    padding-right: 57px;
                    box-sizing: border-box;
                    .word-title{
                        font: 27px/61px "黑体";
                    }
                    .time{
                        font: 19px/83px "黑体";
                    }
                    .des{
                        color: #666666;
                        font: 16px/46px "微软雅黑";
                    }
                }
            }
        }
    }
</style>
