<template>
    <div class="video-wrap">
        <div class="video">
            <div class="video-logo"></div>
            <div class="video-word">
                <div class="title">全球区块链研究会成立发布会</div>
                <div class="time">2018.09.30 23:30</div>
                <div class="des">
                    介绍：全球区块链研究会成坚持就是不能参加手机全球区块链研究会成坚持就是不能参加手机全球区块链研究会成坚持就是不能参加手机全球区块链研究会成坚持就是不能参加手机全球区块链研究会成坚持就是不能参加手机全球区块链研究会成坚持就是不能参加手机
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'IndexVideo'
}
</script>
<style lang="less" scoped>
    .video-wrap{
        width: 100%;
        background: #fafbff;
        .video{
            width: 1204px;
            height: 600px;
            margin: 0 auto;
            padding-top: 60px;
            box-sizing: border-box;
            .video-logo{
                width: 642px;
                height: 480px;
                float: left;
                background: url(../../../assets/imgs/video.png) no-repeat;
            }
            .video-word{
                width: 562px;
                height: 540px;
                float: left;
                box-sizing: border-box;
                padding: 48px 30px 48px 30px;
                .title{
                    font: 32px/87px "微软雅黑";
                }
                .time{
                    color: #4b75ff;
                    margin-bottom: 15px;
                    font: 24px/64px "微软雅黑";
                }
                .des{
                    font: 18px/46px "微软雅黑";
                }
            }
        }
    }
</style>
