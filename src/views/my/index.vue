<template>
    <div class="my-container">
        <div class="header not-login">
          <div class="login-btn" @click="$router.push('/login')">
            <img class="mobile-img" src="~@/assets/mobile.png" alt="">
            <span class="text">登录 / 注册</span>
          </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'MyIndex',
  data () {
    return {

    }
  },
  created () {

  },
  mounted () {

  },
  methods: {

  }
}
</script>

<style scoped lang="less">
.my-container {
  .header {
    height: 361px;
    background: url("~@/assets/banner.png");
    background-size: cover;
  }
  .not-login {
    display: flex;
    justify-content: center;
    align-items: center;
    .login-btn {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      .mobile-img {
        width: 132px;
        height: 132px;
      }
      .text {
        margin-top: 15px;
        font-size: 28px;
        color: #fff;
      }
    }
  }
}
</style>
