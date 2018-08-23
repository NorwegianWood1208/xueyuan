<template>
    <div class="techao-wrap">
        <div class="techao">
            <div class="title">
                Technological Architecture
            </div>
            <div class="sanjiao">
                <img src="../assets/imgs/切图/多边形2.png" alt="">
            </div>
            <div class="lis1">
                <img src="../assets/imgs/切图/gif4.gif" alt="">
                <div class="des">
                    <div class="des-title">Consensus algorithm</div>
                    <div class="des-con">NAIL utilizes decentralized consensus algorithm of DPos to resolve the issues of traditional Pow and Pow on mechanism, besides, it also offsets the negative effects bought about by centralization by means of implementation of technology based democracy.</div>
                </div>
            </div>
            <div class="lis2">
                <img src="../assets/imgs/切图/gif1.gif" alt="">
                <div class="des">
                    <div class="des-title">Privacy</div>
                    <div class="des-con">Whatever the types, UTXO and account model have their respective merits and disadvantages , however, the persistent problem needs to be solved is the anonymity. The bottom data storage model is based on the account model with ZSL ( zero-knowledge security layer), as a result, the trading privacy is protected and only the holders of the trading can finish it with private key and inquiry their own trading and thus, the issues on privacy are well resolved.</div>
                </div>
            </div>
             <div class="lis1">
                <img src="../assets/imgs/切图/gif3.gif" alt="">
                <div class="des">
                    <div class="des-title">Shard</div>
                    <div class="des-con">In the decentralized network, every and the whole node will store more data, therefore, large amount of expenditures are spent on the data storage, which results in the biggest bottleneck in blockchain applications. NAIL will use different tactics and divide the data into shard and store into the node through decentralized means to resolve existing problems.</div>
                </div>
            </div>
            <div class="lis2">
                <img src="../assets/imgs/切图/gif2.gif" alt="">
                <div class="des">
                    <div class="des-title">Contract</div>
                    <div class="des-con">The contract of NAIL does not provide its own contract, rather than it is a cluster layer in the whole framework and integrate the virtual machine into the NAIL by RPC to support the contract language of the third party. NAIL seamlessly integrates EVM, which means that these contracts directly access to NAIL ecology and by means of adaption layer of contract layer and platform node for trading.</div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'IndexTechao'
}
</script>
<style lang="less" scoped>
    .techao-wrap{
        width: 100%;
        background: #fff;
        .techao{
            width: 1500px;
            // height: 1824px;
            margin:  0 auto;
            padding-top: 55px;
            box-sizing: border-box;
            .title{
                text-align: center;
                font: 30px/86px "微软雅黑";
            }
            .sanjiao{
                width: 100%;
                height: 96px;
                text-align: center;
            }
            .lis1{
                width: 1500px;
                height: 400px;
                img{
                    height: 400px;
                    width: 500px;
                    float: left;
                    margin-left: 30px;
                }
                .des{
                    width: 778px;
                    height: 400px;
                    float: right;
                    padding-top: 50px;
                    box-sizing: border-box;
                    .des-title{
                        width: 100%;
                        font: 20px/100px "微软雅黑";
                    }
                    .des-con{
                        width: 100%;
                        font: 16px/30px "微软雅黑";
                    }
                }
            }
            .lis2{
                width: 1500px;
                height: 400px;
                img{
                    height: 400px;
                    width: 500px;
                    float: right;
                    margin-left: 30px;
                }
                .des{
                    width: 778px;
                    height: 400px;
                    float: left;
                    padding-top: 50px;
                    box-sizing: border-box;
                    .des-title{
                        width: 100%;
                        font: 20px/100px "微软雅黑";
                    }
                    .des-con{
                        width: 100%;
                        font: 16px/30px "微软雅黑";
                    }
                }
            }
        }
    }
</style>
