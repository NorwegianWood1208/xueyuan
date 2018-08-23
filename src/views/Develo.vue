<template>
    <div class="develo-wrap">
        <div class="develo">
            <div class="title">Development</div>
            <div class="des">Initiation of Blockchain Landmark  Project Preparedness Project Road Show</div>
            <div class="xian">
                <div class="dian"></div>
                <div class="dian"></div>
                <div class="dian"></div>
                <div class="dian"></div>
                <div class="dian"></div>
                <div class="dian"></div>
                <div class="dian"></div>
                <div class="dian"></div>
                <div class="dian nomargin"></div>
            </div>
            <div class="one">
                <div class="lis">
                    <div class="time">2018.2</div>
                    <div class="shi">Preparation plan</div>
                </div>
                <div class="lis">
                    <div class="time">2018.8</div>
                    <div class="shi">Official Launch , Global Road Show</div>
                </div>
                <div class="lis">
                    <div class="time">2018.7</div>
                    <div class="shi">Public placement for global recruitment of volunteers</div>
                </div>
                <div class="lis">
                    <div class="time">2018.08</div>
                    <div class="shi">NAIL Japan Road Show</div>
                </div>
            </div>
            <div class="two">
                <div class="lis">
                    <div class="time">2018.7</div>
                    <div class="shi">Introduction of strategic investors</div>
                </div>
                <div class="lis">
                    <div class="time">2018.08</div>
                    <div class="shi">Introduction of strategic investors</div>
                </div>
                <div class="lis">
                    <div class="time">2018.08</div>
                    <div class="shi">Public blockchain v.10 goes online</div>
                </div>
                <div class="lis">
                    <div class="time">2018.08</div>
                    <div class="shi">NAIL Japan Road Show</div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'IndexDevelo'
}
</script>
<style lang="less" scoped>
    #app .nomargin{
        margin-right: 0
    }
    .develo-wrap{
        width: 100%;
        height: 620px;
        background: url(../assets/imgs/切图/dev背景.png) no-repeat;
        background-size: 100%;
        
        .develo{
            width: 1500px;
            height: 620px;
            position: relative;
            margin: 0 auto;
            .title{
                color: #fff;
                padding-left:112px;
                padding-top: 117px; 
                font: 36px/86px "微软雅黑";
            }
            .des{
                color: #fff;
                margin-bottom: 70px;
                padding-left:112px; 
                font: 20px/40px "微软雅黑";
            }
            .xian{
                width: 1220px;
                height: 50px;
                position: absolute;
                top: 350px;
                left: 128px;
                border-bottom: 1px dashed #fff;
                .dian{
                    width: 12px;
                    height: 12px;
                    float: left;
                    margin-right: 139px;
                    margin-top: 43px;
                    background: #fff;
                    border-radius: 8px;
                }
            }
            .one{
                width: 100%;
                overflow: hidden;
                padding-left: 125px;
                .lis{
                    width: 300px;
                    height: 56px;
                    color: #fff;
                    float: left;
                    .time{
                        font: 12px/26px "微软雅黑";
                    }
                    .shi{
                        font: 14px/40px "微软雅黑";
                    }
                }
            }
            .two{
                margin-top: 60px;
                overflow: hidden;
                box-sizing: border-box;
                margin-left: 265px;
                .lis{
                    width: 300px;
                    height: 56px;
                    color: #fff;
                    float: left;
                    .time{
                        font: 12px/26px "微软雅黑";
                    }
                    .shi{
                        font: 14px/40px "微软雅黑";
                    }
                }
            }
        }
    }
</style>