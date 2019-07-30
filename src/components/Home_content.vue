<template>
  <div class="content">
      <el-row :gutter=0 class="rowLine">
        <el-col :xs="6" :sm="6" :md="6" :lg="6" :xl="6" class="silver">
          <img src="../assets/HOME/02_Home_12.png" alt="img">
        </el-col>
        <el-col :xs="6" :sm="6" :md="6" :lg="6" :xl="6" class="lightS">
          <img src="../assets/HOME/02_Home_06.png" alt="img">
        </el-col>
        <el-col :xs="6" :sm="6" :md="6" :lg="6" :xl="6" class="lower">
          <img src="../assets/HOME/h.png" alt="img">
        </el-col>
        <el-col :xs="6" :sm="6" :md="6" :lg="6" :xl="6" class="lightS">
          <img src="../assets/HOME/02_Home_09.png" alt="img">
        </el-col>
      </el-row>
      <el-row :gutter=0 class="rowLine">
        <el-col :xs="6" :sm="6" :md="6" :lg="6" :xl="6" class="lightS">
          <img src="../assets/HOME/02_Home_17.png" alt="img" class="specialImg">
        </el-col>
        <el-col :xs="6" :sm="6" :md="6" :lg="6" :xl="6" class="special">
            <img src="../assets/HOME/02_Home_03.png" alt="eyes"  class="specialImg">
        </el-col>
        <el-col :xs="6" :sm="6" :md="6" :lg="6" :xl="6" class="lightS">
          <img src="../assets/HOME/02_Home_26.png" alt="img">
        </el-col>
        <el-col :xs="6" :sm="6" :md="6" :lg="6" :xl="6" class="lower">
          <img src="../assets/HOME/02_Home_23.png" alt="img">
        </el-col>
      </el-row>
      <el-row :gutter=0 class="rowLine">
        <el-col :xs="6" :sm="6" :md="6" :lg="6" :xl="6" class="lower">
          <img src="../assets/HOME/2.png" alt="img">
        </el-col>
        <el-col :xs="6" :sm="6" :md="6" :lg="6" :xl="6" class="lightS">
          <img src="../assets/HOME/3.png" alt="img">
        </el-col>
        <el-col :xs="6" :sm="6" :md="6" :lg="6" :xl="6" class="lower">
          <img src="../assets/HOME/02_Home_14.png" alt="img" class="specialImg">
        </el-col>
        <el-col :xs="6" :sm="6" :md="6" :lg="6" :xl="6" class="lightS">
          <img src="../assets/HOME/02_Home_26.png" alt="img">
        </el-col>
      </el-row>
  </div>
</template>

<script>
export default {
}

</script>
<style lang='less' scoped>
.rowLine{
    height: 275px;
    width: 100%;
}
.el-col{
    position: relative;
    height: 100%;
    // display: flex;
    // justify-content: center;
    // align-items: center;

}
.silver{
    background-color : #e7e6e4
}
.lower{
  background-color: #e1e1e1;
}
.lightS{
    background-color: #eeeeee
}
.special{
    background-color: #21bfb9;
}
.specialImg{
  width: 25%;
  height: auto;
}
img{
  width: 50%;
  height: auto;
    position: absolute;
    //  left: 50%;
    //     top: 50%;
    //     transform: translateX(-50%) translateY(-50%);
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    margin: auto;
}
</style>
