<template>
  <dv-full-screen-container class="page-container">
    <el-container>
      <el-header class="top-header"></el-header>
      <el-main class="main-container">
        <el-row :gutter="10" style="width: 100%; height: 100%">
          <el-col :span="6" class="left">
            <div class="box">
              <dv-border-box-8>dv-border-box-8</dv-border-box-8>
            </div>
            <div class="box">
              <dv-border-box-8>dv-border-box-8</dv-border-box-8>
            </div>
            <div class="box">
              <dv-border-box-8>dv-border-box-8</dv-border-box-8>
            </div>
          </el-col>
          <el-col :span="12" class="center">
            <dv-border-box-8>dv-border-box-8</dv-border-box-8>
          </el-col>
          <el-col :span="6" class="right">
            <div class="box">
              <dv-border-box-8>dv-border-box-8</dv-border-box-8>
            </div>
            <div class="box">
              <dv-border-box-8>dv-border-box-8</dv-border-box-8>
            </div>
            <div class="box">
              <dv-border-box-8>dv-border-box-8</dv-border-box-8>
            </div>
          </el-col>
        </el-row>
      </el-main>
    </el-container>
  </dv-full-screen-container>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>
<style lang="less" scoped>
.page-container {
  background-image: url("../assets/img/pageBg.png");
  background-size: cover;
  background-position: center center;
  .top-header {
    width: 100%;
    height: 80px;
    background: rgba(255, 255, 255, 0.3);
  }
  .main-container {
    width: 100%;
    height: calc(100vh - 60px);
  }
  .left,
  .center,
  .right {
    height: 100%;
  }
  .box {
    height: 280px;
  }
}
</style>
