<template>
  <div class="content">
      <el-row :gutter="0" class="title">
          <el-col :span="6">
              <img src="../assets/About/one.png" alt="icon" class="icon">
              <div class="right">
                  <div><img src="../assets/About/548.png" alt="word"></div>
                  <img src="../assets/About/projects-completed.png" alt="word" class="num">
              </div>
          </el-col>
          <el-col :span="6">
              <img src="../assets/About/two.png" alt="icon" class="icon">
              <div class="right">
                  <div><img src="../assets/About/612.png" alt="word"></div>
                  <img src="../assets/About/WORKING-HOURS.png" alt="word" class="num">
              </div>
          </el-col>
          <el-col :span="6">
              <img src="../assets/About/three.png" alt="icon" class="icon">
              <div class="right">
                  <div><img src="../assets/About/735.png" alt="word"></div>
                  <img src="../assets/About/POSITIVE-FEEDBACKS.png" alt="word" class="num">
              </div>
          </el-col>
          <el-col :span="6">
              <img src="../assets/About/four.png" alt="icon" class="icon">
              <div class="right">
                  <div><img src="../assets/About/1465.png" alt="word"></div>
                  <img src="../assets/About/HAPPY-CLIENTS.png" alt="word" class="num">
              </div>
          </el-col>
      </el-row>
      <el-row :gutter="0" class="main">
          <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12" class="special"><img src="../assets/About/03_About_02.png" alt="img"></el-col>
          <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12">
              <div class="right">
                  <div class="fir"><img src="../assets/About/03_About_07.png" alt="word"></div>
                  <img src="../assets/About/five.png" alt="word">
                  <div class="thir"><img src="../assets/About/03_About_11.png" alt="word"></div>
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
.title{
    height: 200px;
    background-color: #10c9c3;
}
.main{
    height: 568px;
}
.el-col{
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.right{
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: start;
    margin-left: 20px;
}
.icon{
    width: 12%;
    height: auto;
}
.num{
    width: 100%;
    height: auto;;
}
img{
    // flex-shrink: 0;
    margin-top: 10px;
}
// 内容
.main{
    background-color: #f5f5f5;
}
.main img{
    text-align: start;
    margin-top: 0;
}
.special{
    justify-content: flex-start;
}
.special>img{
    width: 100%;
    height: auto;
    max-height: 568px;
}
.fir{
    margin-bottom: 30px;
    object-fit: contain;
}
.thir{
    margin-top: 50px;
}
</style>
