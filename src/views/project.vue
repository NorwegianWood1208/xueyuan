<template>
    <div class="project-wrap">
        <div class="project">
            <div class="title">
                Project Scheme
            </div>
            <div class="sanjiao">
                <img src="../assets/imgs/切图/protop.png" alt="">
            </div>
            <div  class="content">

            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'IndexProject'
}
</script>
<style lang="less" scoped>
    .project-wrap{
        width: 100%;
        height: 650px;
        background: url(../assets/imgs/切图/pro背景.png) no-repeat;
        background-size:100%; 
        .project{
            width: 1500px;
            height: 650px;
            margin:  0 auto;
            .title{
                text-align: center;
                font: 30px/86px "微软雅黑";
            }
            .sanjiao{
                width: 100%;
                height: 96px;
                text-align: center;
            }
            .content{
                width: 1360px;
                height: 475px;
                border-top: 2px dashed #dbdcde;
            }
        }
    }
</style>
