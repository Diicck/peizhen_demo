<script>
export default {
  methods:{
    login(){
      this.$router.push('/home')
    }
  }
}

</script>

<template>
  <el-container>
    <el-main>
      <el-col :span="6">
      <el-card shadow="hover">

        <el-input
            placeholder="请输入用户名"

            clearable>
        </el-input>

        <el-input
            placeholder="请输入密码"

            show-password>
        </el-input>

        <el-button @click="login">登录</el-button>

      </el-card>
    </el-col>
    </el-main>
  </el-container>
</template>

<style scoped>
.el-main{
  background: #eeeeee;
}
 .el-card{
   height: auto;

 }

 .el-main{
   display: flex;
   justify-content: center; /* 水平居中 */
   align-items: center; /* 垂直居中 */
 }
 .el-input{
   margin-top:20px ;
 }
 .el-button{
   margin-top: 25px;
 }
</style>