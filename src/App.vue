<template>
  <div id="app">
    <div id="nav">
      <el-row :gutter="10" class="nav">
        <el-col :xs="6" :sm="6" :md="6" :lg="6" :xl="6">
          <el-menu class="nav_left" mode="horizontal">
            <el-menu-item index="1"><img src="./assets/home_03.png" alt="logo" /></el-menu-item>
          </el-menu>
        </el-col>
        <el-col :xs="12" :sm="12" :md="12" :lg="12" :xl="12">
          <el-menu class="nav_right" mode="horizontal">
            <el-menu-item><router-link to="/"><div class="img1"></div></router-link></el-menu-item>
            <el-menu-item><router-link to="/about"><div class="img2"></div></router-link></el-menu-item>
            <el-menu-item><router-link to="/contact"><div class="img3"></div></router-link></el-menu-item>
            </el-menu>
        </el-col>
      </el-row>
    </div>
    <router-view />
  </div>
</template>
<script>
export default {
}
</script>
<style lang="less">
*{
  margin: 0;
  padding: 0;
}
// img{
//   width: 100%;
//   height: auto;
// }
#app {
  text-align: center;
  margin: 0;
  padding: 0;
}
.nav{
  display: flex;
  justify-content: space-between
}
.nav_left{
   margin-left: -29px;
}
.nav_right{
  float: right;
   margin-right: -40px;
}
// 默认导航图片
.img1{
  width: 67px;
  height: 9px;
  background: url(./assets/03_About_03.png) no-repeat;
  margin-top: 20px;
}
.img2{
  width: 67px;
  height: 9px;
  background: url(./assets/02_Home_05.png) no-repeat;
  margin-top: 20px;
}
.img3{
  width: 67px;
  height: 9px;
  background: url(./assets/02_Home_07.png) no-repeat;
  margin-top: 20px;
}
.img1:hover{
  background: url(./assets/02_Home_03.png) no-repeat
}
.img2:hover{
  background: url(./assets/03_About_05.png) no-repeat
}
.img3:hover{
  background: url(./assets/05_Contact_03.png) no-repeat
}
// 选中后激活后的图片
.router-link-exact-active > .img1{
  background: url(./assets/02_Home_03.png) no-repeat
}
.router-link-exact-active > .img2{
  background: url(./assets/03_About_05.png) no-repeat
}
.router-link-exact-active > .img3{
  background: url(./assets/05_Contact_03.png) no-repeat
}
//取消下划线
.el-menu.el-menu--horizontal{
  border:none !important;
}
</style>
