<template>
    <div class="wrap">
      <index-head></index-head>
      <index-layout></index-layout>
      <index-img></index-img>
      <index-global></index-global>
      <index-develo></index-develo>
      <index-techao></index-techao>
      <index-millon></index-millon>
      <index-token></index-token>
      <index-project></index-project>
    </div>
</template>

<script>
// @ is an alias to /src
import IndexHead from './head'
import IndexLayout from './layout'
import IndexImg from './img'
import IndexGlobal from './global'
import IndexDevelo from './Develo'
import IndexTechao from './techao'
import IndexMillon from './millon'
import IndexToken from './token'
import IndexProject from './project'
export default {
  name: 'home',
  components:{
    IndexHead,
    IndexLayout,
    IndexImg,
    IndexGlobal,
    IndexDevelo,
    IndexTechao,
    IndexMillon,
    IndexToken,
    IndexProject
  }
}
</script>
<style lang="less" scoped>
  .wrap{
    width: 100%;
    height: 3500px;
    background: teal;
  }
</style>
