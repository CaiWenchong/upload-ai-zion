<script setup lang="ts">
import uploadAI from "./components/uploadAI.vue";
import { reactive, ref } from "vue";


const globalData = reactive({ componentName: "AI上传文件-zion", });
const setGlobalData = (obj: any) => {
  globalData.componentName = obj.value;
};


// const url = ref("");
// const actionflow_id = ref("5e5e155d-7b3c-4771-bf94-ceb597cbb666");
// const where = ref("");
// const limit = ref(-1);
// const table_name = ref("");

// const url = ref("1");
// const actionflow_id = ref("2");
// const where = ref("3");
// const limit = ref(10);

// const table_name = ref("4");


// const redirectUrl="5"
// const pageFiled="6"
// const pageId="7"



</script>
<template>
  <uploadAI
  
    :global-data="globalData"
    :set-global-data="setGlobalData"
  />

</template>

<style>
#app {
  /* height: 60vh; */
  /* background-color: #ffffff; */
}
</style>
