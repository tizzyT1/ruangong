<template>
  <div id="other">
    <el-container style="background-color: #f7f8f9">
      <el-header style="height: 60px; width: 1280px; padding: 0">
        <Banner></Banner>
      </el-header>
      <el-container style="width: 99%; margin: 5px auto 0; background: #fff">
        <el-aside width="200px">
          <Aside></Aside>
        </el-aside>
        <el-main style="padding: 0"><Content></Content></el-main>
      </el-container>
    </el-container>
  </div>
</template>

<script>
import Banner from "../components/banner.vue";
import Aside from "../components/discuss/aside.vue";
import Content from "../components/other/content.vue";
export default {
  name: "discuss",
  components: {
    Banner,
    Aside,
    Content,
  },
};
</script>

<style lang="scss" scoped>
</style>>

