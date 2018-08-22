<template>
    <div class="wrap">
        <index-head></index-head>
        <index-banner></index-banner>
        <index-video></index-video>
        <index-core></index-core>
        <index-week></index-week>
        <index-herf></index-herf>
        <index-foot></index-foot>
    </div>
</template>
<script>
import IndexHead from './compontent/head'
import IndexBanner from './compontent/banner'
import IndexVideo from './compontent/video'
import IndexCore from './compontent/core'
import IndexWeek from './compontent/week'
import IndexHerf from './compontent/herf'
import IndexFoot from './compontent/foot'
export default {
    name:'Index',
    components:{
        IndexHead,
        IndexBanner,
        IndexVideo,
        IndexCore,
        IndexWeek,
        IndexHerf,
        IndexFoot
    }

}
</script>
<style lang="less" scoped>
    .wrap{
        width: 100%;
    }
</style>
