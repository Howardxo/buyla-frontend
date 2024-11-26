<template>
  <HomeView />
</template>

<script>
import HomeView from './views/HomeView.vue'; // 確保正確導入 HomeView

export default {
  name: 'App',
  components: {
    HomeView,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  /* 避免元素邊框和內邊距影響大小計算 */
}

body {
  margin: 0;
}
</style>
