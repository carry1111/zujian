<style scoped lang="less">
    // @import 'styles/common.less';
    .msg-wrapper{
        width: 100px;
        height: 100px;
    }
    .account{
        font-size: 12px;
    }
</style>
<template>
    <div class="msg-wrapper">
        <span>hello!</span>
        <span class="account">{{data.name}}</span>
    </div>
</template>
<script>
    export default {
        name:'Msg',
        data () {
            return {}
        },
        props:{
            data:{
                type:Object
            }
        },
        methods: {
 
        },
        created(){
            let that = this;
        }
    }
</script>