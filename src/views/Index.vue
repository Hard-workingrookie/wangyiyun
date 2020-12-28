<template>
  <div class="">
    <el-container class="container">
      <el-container class="main">
        <el-aside width="180px">
          <LeftMenu />
        </el-aside>
        <el-main>
          <Main></Main>
        </el-main>
      </el-container>
    </el-container>
  </div>
</template>
<script>
import LeftMenu from "@/views/LeftMenu";
import Header from "@/components/Header";
import Main from "@/views/Main";

export default {
  data() {
    return {};
  },
  components: {
    LeftMenu,
    Header,
    Main,
  },
  created() {
    // this.$http
    //   .get("/api/search/hot")
    //   .then((response) => {
    //     console.log(response.data.result);
    //   })
    //   .catch((error) => {
    //     console.log(error);
    //   });
  },
};
</script>

<style lang='scss' scoped>
.el-header {
  padding: 0 !important;
}
</style>
