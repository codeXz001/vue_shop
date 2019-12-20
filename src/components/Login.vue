<template>
  <div id="login-container">
      <div class="login-box">
        <div class="avatar-box">
          <img src="../assets/logo.png" alt="">
        </div>
        <el-form label-width="80px">
          <el-form-item label="活动名称">
          <el-input ></el-input>
        </el-form-item>
        </el-form>
      </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="less" scoped>
  #login-container{
    background-color: #2b4b6b;
    height: 100%;
}
.login-box{
  width: 450px;
  height: 300px;
  background-color: #fff;
  border-radius: 5px;
  position: absolute;
  top:50%;
  left:50%;
  transform: translate(-50%,-50%)
}
.avatar-box{
  position: absolute;
    left: 50%;
    transform: translate(-50%,-50%);
  width: 130px;
  height: 130px;
  border: 1px solid #ccc;
  padding: 10px;
  border-radius: 50%;
  box-shadow: 0 0 10px #ddd;
  background-color: #fff;
  img{
    width: 100%;
    height: 100%;
    border-radius: 50%;
    background-color: #eee;
  }
}
</style>
