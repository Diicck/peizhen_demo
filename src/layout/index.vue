<script>

export default {
  components:{
    Header:() => import('@/layout/header/index.vue'),
    Aside:()=> import('@/layout/aside/index.vue')
  }
}

</script>

<template>
    <el-container class="is-vertical">
      <Header></Header>
      <el-container>
        <Aside></Aside>
        <el-main>
          Main
        </el-main>
      </el-container>
    </el-container>

</template>

<style>
.el-header, .el-footer {
  background-color: #bedcff;
  color: #333;
  text-align: center;
  line-height: 60px;
}

.el-aside {
  background-color: #ffffff;
  color: #333;
  text-align: center;
}

.el-main {
  background-color: #ffffff;
  color: #333;
  text-align: center;
}

body > .el-container {
  margin-bottom: 40px;
}

.el-container:nth-child(5) .el-aside,
.el-container:nth-child(6) .el-aside {
  line-height: 260px;
}

.el-container:nth-child(7) .el-aside {
  line-height: 320px;
}
.el-container{
  height: 100vh;
}
body{
  margin: 0;
}
</style>