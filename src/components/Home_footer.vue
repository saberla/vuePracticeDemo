<template>
  <div class="footer">
    <el-row :gutter="0">
      <el-col :span="8">
        <div class="first">
          <img src="../assets/HOME/02_Home_08.png" alt="wordImg">
          <span>© 2017 Piroll. All rights reserved. Designed by robirurk.</span>
        </div>
      </el-col>
      <el-col :span="8">
        <div class="second">
          <span>hello@pirolltheme.com +44 987 065 908 </span>
        </div>
      </el-col>
      <el-col :span="4">
        <div class="third">
          <span>Projects About Services Carreer</span>
          <span>News Events Contact Legals</span>
        </div>
      </el-col>
      <el-col :span="4">
        <div class="fourth">
          <span>Facebook Twitter Instagram Dribbble</span>
        </div>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {
}

</script>
<style lang='less' scoped>
.footer{
  width: 100%;
  height: 300px;
  background-color: #141414;
  color: #767676;
  text-align: start;
}
.el-row{
  height: 100%;
}
.el-col{
  // position: relative;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.first{
  width: 253px;
}
.first>img{
  margin-bottom: 15px;
}
.second{
  width: 136px;
  margin-bottom: 43px;
  line-height: 30px;
}
.fourth{
  width: 70px;
  line-height: 30px;
}
span{
  display: block;
}
.third>span{
  display: inline-block !important;
  width: 70px;
  margin-left: 21px;
  line-height: 30px;
}
</style>
