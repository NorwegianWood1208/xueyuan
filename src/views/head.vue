<template>
    <div class="head-wrap">
        <div class="head">
            <router-link to="/"><img class="h1" src="../assets/imgs/h1.png" alt=""></router-link>
            <div class="float-right">
                <nav class="nav">
                    <!-- <div class="lis">{{$t("home")}}</div> -->
                    <!-- <div class="lis">{{$t("Assets")}}</div>
                    <div class="lis">{{$t("Introduction")}}</div> -->
                </nav>
                <!-- <BaseSelect v-on:select="showProject"
                :selectedValue="projectName"
                :dataList="list"
                :widthData="widthData"></BaseSelect> -->
                <div class="lis-login">
                    <div class="btnlogin">Login/</div>
                    <div  class="btnregister">Register</div>
                </div>
            </div>
        </div>
        <div class="swiper">
            <div class="title">
                PAN-ECOLOGY BLOCKCHAIN HATCHING ALLIANCE
            </div>
            <div class="des">
                To Build Digital Currency World in the Global Finance Center
            </div>
            <div class="btn">White paper</div>
            <div class="icon">
                <img src="../assets/imgs/facebook.png" alt="">
                <img src="../assets/imgs/tw.png" alt="">
                <img src="../assets/imgs/推特_twitter43.png" alt="">
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'IndexHead'
}
</script>
<style lang="less" scoped>
    .head-wrap{
        width: 100%;
        height: 1080px;
        background: #2b5fff;
        .head{
            width: 1500px;
            height: 64px;
            padding-top: 15px;
            box-sizing: border-box;
            margin: 0 auto;
            h1{
            margin-left: 40px;
        }
        .float-right{
            float: right;
            position: relative;
            .nav{
                overflow: hidden;
                float: left;
                color: #fff;
                margin-left: 620px;
                .lis{
                    font: 18px/34px "华文细黑";
                    float: left;
                    text-align: center;
                    margin:  0 40px;
                    border-bottom: 1px solid #757575;
                }
            }
            .lis-login{
                overflow: hidden;
                padding:  0 40px;
                float: right;
                margin-left: 300px;
                font: 18px/34px "华文细黑";
                color: #fff;
                    .btnlogin,.btnregister:hover{
                        cursor: pointer;
                    }
                    .btnlogin{
                        float: left;
                        color: #fff;
                    }
                    .btnregister{
                        float: left;
                        color: #fff;
                    }
                }
                .lange{
                    font-size: 16px;
                    float: right;
                    color: #fff;
                    text-align: right;
                    margin-right: 40px;
                    background: #3b3b3b;
                    font: 16px/34px "微软雅黑";
                    -webkit-appearance: none; /*for chrome*/
                    .desfont{
                        background: #3b3b3b;
                        border: none;
                    }
                }
                
            }
        }
        .swiper{
            width: 1500px;
            height: 1016px;
            margin:  0 auto;  
            position: relative;  
            .title{
                width: 800px;
                height: 124px;
                color: #fff;
                position: absolute;
                top: 202px;
                font:bold   36px/64px Montserrat;
            }
            .des{
                width: 470px;
                color: #fff;
                position: absolute;
                top: 330px;
                font:bold 18px/36px Montserrat;
            }
            .btn{
                width: 285px;
                height: 85px;
                color: #fff;
                position: absolute;
                top: 423px; 
                text-align: center;
                border-radius: 80px;
                background: #67a7ff;
                font: 24px/85px Montserrat;
            }
            .icon{
                width: 100%;
                height: 26px;
                position: absolute;
                bottom: 58px;
                padding-left: 10px;
                box-sizing: border-box;
                img{
                    margin-right: 30px;
                }
            }
        }
    }
</style>
