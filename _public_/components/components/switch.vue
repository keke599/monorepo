<template>
  <div>
    <el-switch v-model="value1" />
  </div>
</template>
<script setup>
import "element-plus/dist/index.css";
import { ElSwitch } from "element-plus";
import { ref } from "vue";
const value1 = ref(true);
</script>
<style scoped></style>
