<template>
    <div class="login_container">
         <!-- 头像区域 -->
       <div class="login_box">
         <div class="avatar_box">
           <img src="../assets/logo.png" alt="">
         </div>
         <!-- 表单区域 -->
        <el-form label-width="0px">
          <!-- 用户名 -->
          <el-form-item>
              <el-input ></el-input>
          </el-form-item>
          <!-- 密码 -->
          <el-form-item>
              <el-input ></el-input>
          </el-form-item>
          <!-- 按钮区域 -->
          <el-form-item>
              <el-button type="primary">主要按钮</el-button>
              <el-button type="primary">主要按钮</el-button>
          </el-form-item>
       </el-form>
       </div>     
    </div>
</template>

<script>
export default {
  data() {
    return {
     
    }
  },
  //添加行为，
  methods: {
    
  }
}
</script>

<style lang="less" scoped>
.login_container {
  background-color: #2b5b6b;
  height: 100%;
}
.login_box {
  width: 450px;
  height: 300px;
  background: #fff;
  border-radius: 3px;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  .avatar_box {
    height: 130px;
    width: 130px;
    border: 1px solid #eee;
    border-radius: 50%;
    padding: 10px;
    box-shadow: 0 0 10px #ddd;
    position: absolute;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: #fff;
    img {
      width: 100%;
      height: 100%;
      border-radius: 50%;
      background-color: #eee;
    }
  }
}
.login_form {
  position: absolute;
  bottom: 0;
  width: 100%;
  padding: 0 20px;
  box-sizing: border-box;
}
.btns {
  display: flex;
  justify-content: flex-end;
}
</style>
