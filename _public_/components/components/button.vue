<template>
  <div>
    <el-button @click="add(1, 2)">我是 ElButton</el-button>
  </div>
</template>
<script setup>
import "element-plus/dist/index.css";
import { ElButton } from "element-plus";
import { add } from "mo-utils";
</script>

<style scoped></style>
