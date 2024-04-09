<template>
  <div class="login-bg">
    <div class="login-form">登录界面</div>
  </div>
</template>
<script setup lang="ts"></script>
<style  lang="scss" scoped>
.login-bg {
  width: 100%;
  margin: 0px;
  height: 100%;
  background: url("@/assets/images/login-bg.jpg") no-repeat;
  background-size: 100% 100%;
  background-attachment: fixed;
  .login-form {
    width: 600px;
    height: 400px;
    background-color: red;
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    margin: auto;
    border-radius: $dialog-radius-large;
  }
}
</style>
