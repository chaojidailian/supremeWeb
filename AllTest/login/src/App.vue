<template>
  <div id="app">
    <img src="./assets/left.jpg" alt="左侧图片" />
    <div class="right">
      <nav>
        <ul>
          <img src="./assets/logo.png" alt="logo图片" />
          <li>小米账号</li>
          <li>用户协议</li>
          <li>隐私政策</li>
          <li>帮助中心</li>
          <li>中文简体</li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style scoped>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
.left {
  
}
.right {
  background-color: purple;
}
</style>
