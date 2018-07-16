<template>
  <div>
    <div class="header">
      <div class="header-left">
        <img src="../assets/logo.png" alt="logo">
      </div>
      <div class="header-rigth">
        <a>登录</a>
        <img src="../assets/购物车.png" alt="shopping">
      </div>
    </div>
    <div class="header-breadcrumb-wrap">
      <div class="warp">
        <p>Home</p>
      </div>
      
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="less" scoped>
.header {
  display: flex;
  justify-content: space-between;
  width: 100%;
  max-width: 1280px;
  height: 55px;
  margin: 0 auto;
  padding: 5px 20px 10px 20px;
  .header-left {
    img {
      width: 60px;
      height: 60px;
      margin-left: 20px;
    }
  }
  .header-rigth {
    display: flex;
    align-items: center;
    a {
      cursor: pointer;
      color: #666;
      font-size: 15px;
      margin-right: 10px;
    }
    img {
      width: 40px;
      height: 40px;
    }
  }
}
.header-breadcrumb-wrap {
  background: #f0f0f0;
  font-size: 1.4rem;
  color: #605F5F;
  padding: 10px 0;
  .warp {
    width: 100%;
    max-width: 1280px;
    margin: 0 auto;
    p {
    line-height: 25px;
    font-size: 14px;
  }
  }
  
}
</style>
