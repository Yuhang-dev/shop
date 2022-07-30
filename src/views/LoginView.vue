<template>
  <div class="login-container">
    <div class="container">
      <div class="left-box">左侧图片区</div>
      <!-- 表单区域-->
      <div class="right-box">
        <h3 class="title">标题</h3>
        <!-- 登陆表单-->
        <div class="form-container">
          <el-form>
            <el-input type="number">用户名</el-input>
            <el-input type="password">密码</el-input>
          </el-form>
          <!-- 滑动验证引入-->
        </div>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.login {
}
</style>
