<template>
  <div class="loginApp">
      <el-card class="login-card">
          <h2 class="logo">
              <img src="../../assets/img/logo_index.png" alt="">
          </h2>
          <el-form>
              <el-form-item>
                  <el-input placeholder="请输入手机号"></el-input>
              </el-form-item>
              <el-form-item>
                  <el-input placeholder="请输入验证码" style="width:240px;"></el-input>
                  <el-button style="float:right">发送验证码</el-button>
              </el-form-item>
              <el-form-item>
                  <el-checkbox>我已阅读并同意用户协议和隐私条款</el-checkbox>
              </el-form-item>
              <el-form-item>
                  <el-button type="primary" style="width:100%;">登录</el-button>
              </el-form-item>
          </el-form>
      </el-card>
  </div>

</template>

<script>
export default {

}
</script>

<style lang='less' scoped>
    .loginApp{
        width:100%;
        height: 100vh;
        background:url(../../assets/img/login_bg.jpg) no-repeat;
        background-size:cover;
        display: flex;
        justify-content: center;
        align-items: center;
        .login-card{
            width:400px;
            height: 360px;
            .logo{
                text-align: center;
                img{
                    height: 40px;
                }
            }
        }
    }
</style>
