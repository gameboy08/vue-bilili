<template>
  <div>
    <login-top middleTop="注册bilibili"></login-top>
    <login-text
      label="姓名"
      style="margin:4.167vw 0;"
      rule="^.{6,16}$"
      placeholder="请输入姓名"
    />
    <login-text label="账号" rule="^.{6,16}$" placeholder="请输入账号" />
    <login-text label="密码" placeholder="请输入密码" />
    <login-btn btntext="注册"></login-btn>
  </div>
</template>

<script>
import LoginTop from "@/components/common/LoginTop";
import LoginText from "@/components/common/LoginText";
import LoginBtn from "@/components/common/LoginBtn";

export default {
  components: {
    LoginTop,
    LoginText,
    LoginBtn
  }
};
</script>

<style></style>
