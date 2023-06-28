<template>
  <router-view />
</template>

<script setup lang="ts">
// import debug from '@/utils/debug';

onMounted(() => {
  // 因为debug是存入localStorage中的，刷新页面会从localStorage取出，根据debug控制是否隐藏
  // debug.init();
  // const { username = '', mobile = '' } = auth.getUser();
});
</script>

<style>
#app {
  font-family: Inter, Avenir, Helvetica, Arial, sans-serif;
  font-synthesis: none;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  -webkit-text-size-adjust: 100%;
}
</style>
