<template>
  <div class="index">
  </div>
</template>

<script setup lang="ts">
import { layoutRoutes } from '@/router';
const list = layoutRoutes.filter((item) => item.name && item.name !== 'index');
console.log(list);
</script>

<style lang="less" scoped>
</style>
