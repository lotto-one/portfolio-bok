<template>
  <div id="app">
    <Sidebar />
    <div class="main-content">
      <router-view />
    </div>
  </div>
</template>
<script>
import Sidebar from "./components/Sidebar.vue";
export default {
  components: {
    Sidebar, // 임포트한 사이드바 컴포넌트를 등록
  },
};
</script>

<style>
#app {
  display: flex;
}
</style>
