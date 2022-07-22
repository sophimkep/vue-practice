<template>
  <div class="container">
    <Main></Main>
    <hr>
    <Sider></Sider>
  </div>
</template>

<script>
import Main from "./MainView.vue";
import Sider from "./SideBarView.vue";
export default {
  components: {
    Main,
    Sider,
  },
};
</script>

<style>
.container {
  display: flex;
  margin: auto;
  width: 90%;
  flex: 2;
}
</style>
