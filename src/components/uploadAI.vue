<template>
    <div class="page-wrap">
        123123
    </div>
</template>

<script >
    // 引入
    import { messageControl } from "/src/components/message.js";

    export default {
        name: "uploadAI",
        props: [
            "globalData",
            "url",
            "actionflow_id",
            "table_name",
            "where",
            "limit",
            "pageId",
            "redirectUrl",
            "pageFiled",
        ],
        mounted() {

        },
        data: () => ({

        }),
        computed: {

        },
        methods: {


        },


    };
</script>

<style scoped>
    @import url("//unpkg.com/element-ui@2.13.2/lib/theme-chalk/index.css");

    * {
        -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
    }
</style>