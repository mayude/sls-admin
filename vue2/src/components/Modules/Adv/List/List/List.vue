<template>
    <div class="list">
        <list-data
            ref='list-data'
            :List='list'
            :FieldList='fields'
            :Selection='true'
            :BtnInfo='btn_info'>

        </list-data>
    </div>
</template>

<script>
    import ListJs from './List.js';
    module.exports=ListJs;
</script>
<style scoped lang='less'>
    .demo-form-inline{
        display: inline-block;
        float: right;
    }
    .btm-action{
        margin-top: 20px;
        text-align: center;
    }
    .actions-top{
        height: 46px;
    }
    .pagination{
        display: inline-block;
    }
</style>
