<template>
  <div class="container">
    <header>
      <h1>Welcome to My Personal Website</h1>
    </header>
    <div class="content">
      <h1>欢迎来到个人网站</h1>
      <p>This is the homepage of my personal website.</p>
    </div>
    <footer class="footer">
      <p>版权所有 &copy; 2023 个人网站</p>
      <p>© 2023 My Personal Website. All rights reserved.</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/** {*/
/*  margin: 0;*/
/*  padding: 0;*/
/*}*/
/*html, body {*/
/*  height: 100%;*/
/*}*/
.container {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  min-height: 100%;
  background-color: #f2f2f2;
}
header {
  background-color: #333;
  color: #fff;
  padding: 30px 0;
  text-align: center;
}
.content {
  text-align: center;
  margin-bottom: 50px;
}
.content h1 {
  font-size: 36px;
  margin-bottom: 20px;
}
.content p {
  font-size: 18px;
  line-height: 1.5;
  margin-bottom: 20px;
}
.footer {
  background-color: #333;
  color: #fff;
  padding: 40px 0;
  text-align: center;
  width: 100%;
}
</style>
