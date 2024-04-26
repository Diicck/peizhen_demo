<script setup>

</script>

<template>

  <el-aside width="300px">
    <el-row class="tac">
      <el-col :span="24">
        <el-menu
            default-active="1"
            class="el-menu-vertical-demo"
        >
          <el-menu-item index="1">
            <span slot="title">导航1</span>
          </el-menu-item>
          <el-menu-item index="2">
            <span slot="title">导航2</span>
          </el-menu-item>
          <el-menu-item index="3">
            <span slot="title">导航3</span>
          </el-menu-item>
          <el-menu-item index="4">
            <span slot="title">导航4</span>
          </el-menu-item>
          <el-menu-item index="5">
            <span slot="title">导航5</span>
          </el-menu-item>
          <el-menu-item index="6">
            <span slot="title">导航6</span>
          </el-menu-item>
        </el-menu>
      </el-col>
    </el-row>


  </el-aside>

</template>

<style scoped>
.el-col{
  height: max-content;
}

</style>
